<template>
    <br>
    <div class="container-md p-1 card ">

        <div class="row">
            <div class=" col col-md-5">
            </div>
            <div class="col-auto ">
                <h2>Checkout</h2>
            </div>
        </div>
    </div>
    <br>
    <div class="col p-1">
        <div class="row">
            <div class="col-auto col-md-6  px-2  card">
                <div id="shipping-info">
                    <div class="text-center"><p><h4>Delivery address</h4></p></div>

                    <div class="input-group mb-3">
                        <span class="input-group-text" id="username">City</span>
                        <input type="text" class="form-control" placeholder="City" aria-label="First Name"
                               aria-describedby="basic-addon1">
                    </div>
                    <div class="input-group mb-3">
                        <span class="input-group-text" id="username">Address</span>
                        <input type="text" class="form-control" placeholder="Address" aria-label="First Name"
                               aria-describedby="basic-addon1">
                    </div>
                    <div class="input-group mb-3">
                        <span class="input-group-text" id="username">Phone</span>
                        <input type="text" class="form-control" placeholder="Phone" aria-label="First Name"
                               aria-describedby="basic-addon1">
                    </div>


                    <div class="d-grid gap-2 py-2">
                        <button type="submit" class="btn btn-primary  bt btn-block"> Submit</button>
                    </div>
                    <!--                    </form>-->
                </div>
            </div>

            <div class="col-auto col-md-6 px-2 card">

                <div class="row  p-2">
                    <div class="col-md-5 p-3">
                        <a class="btn btn-outline-primary" href="/"> &lt;- Back to Cart</a>
                    </div>
                    <div class="col-md-4">
                        <p><h2><strong>Cart</strong></h2></p>
                    </div>
                </div>
                <table class="table">
                    <thead>
                    <tr>
                        <th scope="col">Image</th>
                        <th scope="col">Item</th>
                        <th scope="col">Price</th>
                        <th scope="col">Quantity</th>
                        <th scope="col">Total</th>
                    </tr>
                    </thead>
                    <tbody>
                    <!--                    {% for elem in items %}-->
                    <tr>
                        <th scope="row"><img src="../images/Xiaomi-Mi-Notebook-Pro-15-2020-Intel-0_large.jpg"
                                             style="width: 50px ; height: 50px">
                        </th>
                        <td><p class="px-lg-2"> Xiaomi notebook PRO</p></td>
                        <td><p class="px-lg-2"> 1000</p></td>
                        <td><p class="px-lg-2"> 1</p></td>
                        <td><p class="px-lg-2">1000 </p></td>
                    </tr>
                    <!--                    {% endfor %}-->
                    </tbody>

                </table>
                <div class="row-auto">
                    <table class="table">
                        <tr>
                            <th><h5>Items: <strong>1</strong></h5></th>
                            <th><h5>Total: <strong>1000</strong></h5></th>
<!--                            {#-->
                            <th><a style="float: right;margin: 5px" class="btn btn-success"
                                    href="">Back to Cart </a></th>
<!--                            #}-->
                        </tr>
                    </table>
                </div>
            </div>
        </div>
        </div>
</template>

<script>
export default {
    name: "checkout"
}
</script>

<style scoped>

</style>
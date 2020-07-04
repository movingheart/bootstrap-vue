<template>
    <div class="jumbotron">
            <div>
                <form>
                    <label for="exampleUsername">Search Github Users</label>
                    <div class="row">
                        <div class="col-6">
                            <div class="form-group">
                                <input type="text" class="form-control" id="exampleUsername">
                            </div>
                        </div>
                        <div class="col-6">
                            <button type="submit" class="btn border">提交</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
</template>

<script>
    export default {
        name: "Search"
    }
</script>

<style scoped>

</style>
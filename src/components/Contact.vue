<template>
    <section id="contact" class="container">
        <div class="row">
            <h1 class="display-4 mx-auto">Contact</h1>
        </div>
        <div class="row">
            <div class="col-md-6 mx-auto">
                <form
                    name="contact-me"
                    method="post"
                    data-netlify="true"
                    data-netlify-honeypot="bot-field"
                >
                    <input type="hidden" name="form-name" value="contact-me" />
                    <div class="form-group">
                        <!--<label for="name">Name</label>-->
                        <input class="form-control" type="text" id="name" placeholder="Name">
                    </div>
                    <div class="form-group">
                        <!--<label for="exampleInputEmail1">Email address</label>-->
                        <input type="email" class="form-control" id="email" placeholder="Email">
                    </div>

                    <div class="form-group">
                        <!--<label for="message">Example textarea</label>-->
                        <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Submit</button>
                </form>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "Contact"
    }
</script>

<style lang="scss" scoped>

</style>

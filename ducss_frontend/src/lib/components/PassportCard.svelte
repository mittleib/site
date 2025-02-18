<script lang="ts">

    export let name : String = "Product Name";
    export let description : String = "Lorem ipsum dolor sit amet, conse";
    export let image : String = "https://images.unsplash.com/photo-1585533530535-2f4236949d08?q=80&w=1287&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D";

</script>

<div class="card">
    <div class="image" style="background-image: url({image})"/>
    <div class="details">
        <h1 class="name"> {name} </h1>
        <h2 class="description"> {description} </h2>
    </div>
</div>

<style>

    * {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }

    .card {
        display: inline-block;
        width: 250px;
        height: 325px;
        background-color: hsl(150, 100%, 98%);
        box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15), 0 3px 6px rgba(0, 0, 0, 0.10);
        padding-top: 10px;
        border-radius: 15px;
        transition: box-shadow 750ms ease-in-out;
        cursor:pointer;
    }

    .card:hover {
        display: inline-block;
        width: 250px;
        height: 325px;
        background-color: hsl(150, 100%, 98%);
        box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
        padding-top: 10px;
        border-radius: 15px;
    }

    .image {
        background-size: cover;
        height: 250px;
        width: 230px;
        margin-left: 10px;
        border-radius: 10px;
    }

    .details {
        padding: 0 20px;
        margin-top: -8px;
    }

    .name {
        font-size: 20px;
        font-weight: 600;
        text-align: left;
        margin-bottom: 5px;
        letter-spacing: -0.05em;
        color: hsl(209, 15%, 28%);
    }

    .description {
        font-size: 16px;
        font-weight: 500;
        text-align: left;
        margin-top: -10px;
        letter-spacing: -0.05em;
        color: hsl(208, 12%, 58%);
    }

</style>

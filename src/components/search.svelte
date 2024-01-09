<script>
    import src from '../assets/search_icon.svg'; 
</script>

<style>
    .search-container{
        width: 240px;
        height: 20px;
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 12px 40px 12px 60px; 
        background: #373737; 
    }

    img{
        width: 20px;
        height: 20px; 
    }

    input{
        background-color: transparent;
        border: none;
        font-family: inherit;
        color: white;
        padding: 5px 5px;
        font-size: 14px;
    }

    input:focus{
        border-radius: 5px;
        border: 1px solid white;
        outline: none;
    }
</style>

<div class="search-container">
    <img {src} alt="">
    <input placeholder="Search for anything">
</div>
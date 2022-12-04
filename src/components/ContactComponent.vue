<template>
    <p>
        contact component
    </p>
    <div>
        <form>
            <Label>Name</Label><input type="text" placeholder="name" class="sublabel"><br><br>
            <Label>Email</Label><input type="text" placeholder="Email" class="sublabel"><br><br>
            <Label>comment</Label><input type="text" placeholder="talk to your club" class="inputy"><br><br><br>
            <input type="button" class="ttt" value="SUBMIT">
        </form>
    </div>
    </template>
    
    <script>
    export default {
        name: 'ContactComponent',
    
    }
    </script>
    
    <style>
    label {
        text-transform: capitalize;
        color: rgb(95, 19, 165);
    }
    
    .inputy {
        width: 65vh;
        height: 20vw;
        border: 2px;
        border-radius: 15%;
        background-color: rgb(245, 243, 240);
        position: center;
        text-align: center;
    }
    
    .ttt {
        font-size: 1rem;
        padding: 0.5em 2em;
    }
    
    .sublabel {
        width: 65vh;
        height: 2vw;
        text-align: center;
        border-radius: 15%;
    
    }
    </style>
    
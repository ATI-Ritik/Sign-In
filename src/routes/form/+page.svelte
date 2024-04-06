<section>
<div class="form">
<div class="header">
    <div class="title">
    <h2>Login</h2>
    <p>Enter your email below to login to your account</p>
    </div>
    
    <div style="margin-left: 20px; margin-top: 30px;">
    <label for="email" >Email</label><br>
    <input type="email" id="email" name="email" placeholder="m@example.com">
    </div>

    <div style="margin-left: 20px; margin-top: 20px;">
        <label for="password" >Password</label><br>
        <input type="password" id="password" name="password">
    </div>
    <div>
        <button class="sign-in">Sign in</button>
    </div>
    

</div>

</div>


</section>

<style>
    section{
        background-color: black;
        height: 200vh;
        border-style: solid;
        border-width: 1px;
        border-radius: 10px;
        border-color: brown;
        color: white;
        font-family: Arial, Helvetica, sans-serif;
    }
    .form {
        display: flex;
        border-style: solid;
        border-width: 1px;
        border-radius: 10px;
        border-color: rgba(194, 194, 194,0.2);
        width: 400px;
        margin-left: 300px;
        margin-top: 250px;
        margin-right: 300px;
        flex-direction: column;
    }
    .title{
        margin-left: 20px;
        margin-bottom: 5px;
        text-align: left;
        flex: 1;
    }
    h2{
        font-size: 24px;
        font-weight: 700;
        margin-top: 30px;
    }
    p{
        margin-top: 0;
        color: rgba(236, 236, 236,0.5)
    }
    #email{
        width: 90%;
        padding: 5px;
        background-color: black;
        border-radius: 5px;
        margin-top: 5px;
        border-style: solid;
        border-width: 1px;
        border-color: rgba(194, 194, 194,0.2);
    }
    #email::placeholder{
        padding-left: 5px;
    }
    #password{
        width: 90%;
        padding: 5px;
        background-color: black;
        border-radius: 5px;
        margin-top: 5px;
        border-style: solid;
        border-width: 0.05px;
        border-color: rgba(194, 194, 194,0.2);
    }
    .sign-in {
        width: 88%;
        padding: 8px;
        background-color: rgb(255, 255, 255);
        color: black;
        border-radius: 5px;
        margin-top: 25px;
        margin-left: 20px;
        margin-bottom: 30px;
        border-style: solid;
        border-width: 0.05px;
        cursor: pointer;
    }

    @media (max-width: 800px) {
    .form{
        margin-left: 4px;
        }
    }

</style>
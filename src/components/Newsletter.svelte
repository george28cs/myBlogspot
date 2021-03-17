<style>
    input {
        background-color: #fff;
        background-image: none;
        border-radius: 4px;
        border: 1px solid #d9d9d9;
        color: rgba(0, 0, 0, 0.75);
        display: inline-block;
        font-size: 14px;
        height: 32px;
        line-height: 32px;
        list-style: none;
        margin: 0;
        outline: 0;
        padding: 4px 12px;
        width: 100%;
        box-sizing: border-box;
    }

    p {
        font-weight: 300;
        color: #333;
        font-size: 15px;
        margin-bottom: 10px;
    }
    form {
        position: relative;
        width: 100%;
    }

    .btn {
        box-shadow: inset 0px 1px 0px 0px #bee2f9;
        background: linear-gradient(to bottom, #e7ebee 5%, #6f7070, 100%);
        border-radius: 4px;
        display: inline-block;
        cursor: pointer;
        border: 1px solid;
        color: #f76b61;
        font-size: 15px;
        font-weight: bold;
        padding: 6px 24px;
        text-decoration: none;
        text-shadow: 8px 1px 8px #bec1c4;
        width: 250px;
    }

    .btn:hover {
        background: linear-gradient(to bottom, #454647 5%, #d5d8da, 100%);
        background-color: #e1e4e7;
    }
    .btn:active {
        position: relative;
        top: 1px;
    }

</style>

<div class="Newsletter">
    <h2>Newsletter</h2>
    <p>Recibe novedades sobre backend y tecnología en tu correo.</p>
    <form 
        action="https://tinyletter.com/george28cs" 
        method="post" target="popupwindow" 
        onsubmit="window.open('https://tinyletter.com/george28cs', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true"><p>
        </p><p>
        <input type="text" style="width:250px" name="email" id="tlemail" placeholder="Escribe tu correo"/></p>
        <input type="hidden" value="1" name="embed"/>
        <button class="btn" type="submit" value="Subscribe" >Suscribirse</button>
        <p>No enviamos spam.</p>    
    </form>

</div>

body {
    font-family: 'Comic Sans MS', cursive, sans-serif;
    background-color: #ffe6e6;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
}

header {
    background-color: #ff9999;
    width: 100%;
    text-align: center;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

header h1 {
    color: #fff;
    margin: 0;
}

main {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.note {
    background-color: #ffcccb;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.2s;
}

.note:hover {
    transform: scale(1.1);
}

.note p {
    margin: 0;
    font-size: 1.2em;
    color: #b30000;
}

footer {
    background-color: #ff9999;
    width: 100%;
    text-align: center;
    padding: 10px;
    box-shadow: 0 -4px 8px rgba(0,0,0,0.1);
}

footer p {
    color: #fff;
    margin: 0;
}

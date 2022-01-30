# card3.0
html{
    --topic_color_1: #00C6FB;
    --topic_color_2: #A3BDED;
    --topic_color_3: #6991C7;
    background-image: linear-gradient(45deg, var(--topic_color_1) 0%, var(--topic_color_2) 56%, var(--topic_color_3) 100%);
}
#main{
    background-image: url("/e3d762ea8b1577a44b7b8b346e47e403/img/1.png");
    background-size:100%;
    height: calc(6vmin * 9);
    width: calc(6vmin * 16);
    pointer-events: none;
}
#start{
    display: grid;
    grid-template-columns: 6fr 4fr;
    height: calc(20vmin * 3);
    width: calc(20vmin * 4);
    align-items: center;
    justify-items: center;
}
#nxt-page{
    position: absolute;
    visibility: hidden;
    z-index: 999;
    font-weight: bolder;
    top: 65%;
    left: 75%;
    background-color: white;
    color: black;
}
.left{
    text-align: center;
    font-size: 5vmin;
    padding: 5vmin;
    padding-right: 6vmin;
    border-right: .1vmin solid rgba(0,0,0,.5);
}
.btn:nth-child(1)
{
    background-color: var(--topic_color_1);
}
.btn:nth-child(2)
{
    background-color: var(--topic_color_2);
}
.btn:nth-child(3)
{
    background-color: var(--topic_color_3);
}
button b{
    font-size: 2vmin;
}

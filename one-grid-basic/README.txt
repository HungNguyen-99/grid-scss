.container {
    display: grid;
    grid-template-columns: 300px 100px 200px;
    grid-template-rows: 100px 200px 100px;
}

mình cũng có thể set các giá trị tương đối thay vì thuyệt đối
.container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr; fraction (Phân số)
    grid-template-rows: 100px 200px 100px;
}
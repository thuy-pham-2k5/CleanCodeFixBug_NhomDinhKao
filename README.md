## Phần 1
### Câu 1
function sum (num1, num2) {
    return num1 + num2;
}

### Câu 2
function getCircle(d) {
    return d  * Math.PI;
}

### Câu 3
function evalNum (num) {
    if (num%2 === 0) {
        return "Chẵn";
    } else {
        return "Lẻ";
    }
}

### Câu 4
function compValues (value1, value2) {
    return value1 === value2;
}

### Câu 5
function checkNumber (num) {
return num > 0;
}

## Phần 2
### Câu 6
function greeting (session, name, wish) {
    return "Chào buổi " + session + ", " + name + "! Chúc bạn " + wish;
}

### Câu 7
function handleData(name, age){
    let adultFlag = false;
    if (age >= 18) {
        adultFlag = true;
    }
    console.log(`Xin chào ${name}, bạn ${adultFlag ? "đã" : "chưa"} đủ tuổi trưởng thành.`);
}

### Câu 8
function canView (user) {
    return (user.role === "admin") || (user.role === "editor" && user.status === "active");
}

### Câu 9
function timesTwo (value) {
    return Math.pow(value, 2);
}

### Câu 10
function showMessage () {
    let greetMessage = "Chào mừng bạn đến với trang web của chúng tôi!"; // Biến toàn cục không khai báo
    console.log(greetMessage);
}
showMessage();

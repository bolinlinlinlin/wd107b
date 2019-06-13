計算的funtion

function result(){
x = document.getElementById("m").value;
y = document.getElementById("kg").value;
z = y/(x*x);
document.getElementById("bmi").value = parseFloat(z.toFixed(2));
}

# kokmade
<!DOCTYPE html>
<html>
<body>
<button>нажмите чтобы ввести данные</button>
<script>window.addEventListener("click", () => {
	
    let a=Number(prompt('Введите день'));
    let b=Number(prompt('Введите месяц'));
    let c=Number(prompt('Введите год'));
    let d=a+b*30*c*365;
    document.write('Вы прожили: '+(d)+' дней');
    
});
</script>
</body>
</html>

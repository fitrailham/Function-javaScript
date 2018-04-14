# Function-javaScript
membahas function

// function factorial(num) {
//   if(num === 1){
//     return 1;
//   }
//   return num * factorial(num - 1);
// }
// /*
// factorial(3)
// 3 * factorial(2)
// 3 * 2 * factorial(1)
// 3 * 2 * 1
// */

// console.log(factorial(6));




function faktorial(n){
	if(n === 1) return 1;
	return n * faktorial(n-1);
}
console.log(faktorial(10));




// //rekursif

// function cetakAngka(n){
// 	if( n === 0) return;
// 	console.log(n);
// 	cetakAngka(n-1);
// }

// cetakAngka(10);





// //variable scope
// var a = 1;

// function tes(){
// 	var b = 2;
// }

// tes();
// console.log(b);



	// //refactoring
	// function jumlahVolumeDuaKubus(a,b){
	// 	return a*a*a + b*b*b;
	// }

	// alert(jumlahVolumeDuaKubus(8,3));



		// // bagiann 4 
		// function tambah() {
		// 	var hasil = 0;
		// 	for(var i = 0; i < arguments.length; i++ ){
		// 		hasil += arguments[i];
		// 	}
		// 	return hasil;
		// }
		// var coba = tambah (1,2,3,4);
		// console.log(coba);



			// //bagian 3
			// function tambah(a,b){
			// 	return a + b;
			// }
			// function kali(a,b){
			// 	return a*b;
			// }

			//  //var a = parseInt(prompt('masukkan angka yang anda ingin kan 1 : '));
			//  //var b = parseInt(prompt('masukkan angka yang anda ingin kan 2 : '));
			//  var total = kali(tambah(3,4), tambah(2,3));
			//  //alert('hasil : '+ total ); 

			//  console.log(total); //untuk runing d console



 				// //bagian 2
				// function jumlahVlolumeDuaKubus(a,b,c,d){
				// 	var total, volumeA, volumeB;

				// 	volumeA = a * a * a;
				//  	volumeB = b * b * b;	

				//  	total = volumeA + volumeB;

				// 	return total;
				// }

				// //console.log(jumlahVlolumeDuaKubus(8,3)); //dalam bentuk console 
				// alert(jumlahVlolumeDuaKubus(8,3)); //dalam bentuk alert
				// alert(jumlahVlolumeDuaKubus(9,5));
				// alert(jumlahVlolumeDuaKubus(12,8));
				// alert(jumlahVlolumeDuaKubus(30,22));



					// //bagian 1
					// var a = 8;
					// var b = 3;
					// var volumeA;
					// var volumeB;
					// var total;

					// volumeA = a * a * a;
					// volumeB = b * b * b;

					// total = volumeA + volumeB;

					// console.log(total);

# Taquitos-
const random =
 Math.floor(Math.random() * 100);

if (random < 40) {

 const r =
  agresivo[Math.floor(Math.random() * agresivo.length)];

 await sock.sendMessage(from, {
   text: r
 });

} else {

 const r =
  personalidad[Math.floor(Math.random() * personalidad.length)];

 await sock.sendMessage(from, {
   text: r
 });

}
node index.js

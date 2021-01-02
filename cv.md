# Resume

## Irina Korbut

1. **Contact Info:**
   phone: +375(29)7510477 (Viber, Tekegram, Watsapp)
   Skype: Korbut Irina
   e-mail: irisharomka96@gmail.com
1. I want to learn front end development and become cool programmer. And I want to improve my skills every day in order to become better and better.
   I ready to study and practice all day and all night.
1. My knowledge and skills: HTML, CSS, JS, GitHub.
1. **Education:** I passed the HTML, CSS and JS basic courses on HTMLacademy and Codecademy. Also I passed RS School front-end training.
1. **English:** My English level is about A2 according to Epam test. I have studied with teacher twice a week since april this year.
1. **Code examples:**
   ```"use strict";
   function formattedPhone(phone) {
   if (!checkIsNumber(phone)) {
   return "Number format is wrong.";
   } else {
   if (phone.length == 12) {
   return (
   phone.slice(0, 2) +
   " (" +
   phone.slice(2, 5) +
   ") " +
   phone.slice(5, 8) +
   "-" +
   phone.slice(8, 10) +
   "-" +
   phone.slice(10)
   );
   } else {
   return "Check the entered number.";
   }
   }
   }
   function checkIsNumber(phone) {
   for (let i = 1; i < phone.length; i++) {
   if (isNaN(parseInt(phone[i]))) {
   return false;
   }
   }
   return true;
   }
   console.log(formattedPhone(prompt("Enter phone number", "+71234567890")));
   ```
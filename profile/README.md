<!DOCTYPE html>
<html xmlns:th="http://www.thymeleaf.org" lang="en">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>TheYoungHana</title>
      <meta name="description" content="사회에 첫 발을 디딘 MZ세대 대학생들을 위한 맞춤형 금융 서비스">
      <meta name="keywords" content="금융, 대학생, MZ세대, 금융 서비스">
      <meta name="author" content="TheYoungHana">
      <meta property="og:title" content="TheYoungHana - 대학생을 위한 금융 생활 동반자">
      <meta property="og:description" content="사회에 첫 발을 디딘 MZ세대 대학생들을 위한 맞춤형 금융 서비스">
      <meta property="og:image" content="https://repository-images.githubusercontent.com/817622930/7e96d62f-3fbc-4c90-abd1-eba331f61291">
      <meta property="og:url" content="https://theyounghana.kro.kr">
      <meta property="og:type" content="website">
      <meta name="twitter:card" content="summary_large_image">
      <meta name="twitter:title" content="TheYoungHana - 대학생을 위한 금융 생활 동반자">
      <meta name="twitter:description" content="사회에 첫 발을 디딘 MZ세대 대학생들을 위한 맞춤형 금융 서비스">
      <meta name="twitter:image" content="https://repository-images.githubusercontent.com/817622930/7e96d62f-3fbc-4c90-abd1-eba331f61291">
      <script src="https://cdn.tailwindcss.com"></script>
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
      <style>
         :root {
         --hana-green: #008C8C;
         --hana-red: #D70037;
         --hana-gold: #B27A3E;
         --hana-silver: #B5B5B5;
         --hana-black: #000000;
         --hana-white: #FFFFFF;
         --hana-pink: #E40054;
         }
         .bg-hana-green { background-color: var(--hana-green); }
         .bg-hana-red { background-color: var(--hana-red); }
         .bg-hana-gold { background-color: var(--hana-gold); }
         .bg-hana-silver { background-color: var(--hana-silver); }
         .bg-hana-black { background-color: var(--hana-black); }
         .bg-hana-white { background-color: var(--hana-white); }
         .bg-hana-pink { background-color: var(--hana-pink); }
         .text-hana-green { color: var(--hana-green); }
         .text-hana-red { color: var(--hana-red); }
         .text-hana-gold { color: var(--hana-gold); }
         .text-hana-silver { color: var(--hana-silver); }
         .text-hana-black { color: var(--hana-black); }
         .text-hana-white { color: var(--hana-white); }
         .text-hana-pink { color: var(--hana-pink); }
         body {
         display: flex;
         flex-direction: column;
         min-height: 100vh;
         }
         main {
         flex: 1;
         }
         body.dark-mode {
         background-color: #1a1a1a;
         color: #e4e4e4;
         }
         body.dark-mode .bg-white {
         background-color: #333;
         }
         body.dark-mode .text-gray-800 {
         color: #e4e4e4;
         }
         table {
         width: 100%;
         border-collapse: collapse;
         box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
         margin-bottom: 20px;
         }
         th, td {
         border: 1px solid var(--hana-silver);
         padding: 12px 15px;
         text-align: left;
         transition: background-color 0.3s ease;
         }
         th {
         background-color: var(--hana-green);
         color: var(--hana-white);
         font-weight: bold;
         }
         table {
         margin-bottom: 16px;
         }
         @media (max-width: 768px) {
         .hide {
         display: none;
         }
         }
         @media (max-width: 753px) {
         .tables-md {
         display: none;
         }
         }
         @media (min-width: 753px) {
         .tables-sm {
         display: none;
         }
         }
      </style>
   </head>
   <body class="bg-gray-100 text-gray-800">
      <main>
         <section class="py-8 md:py-16">
            <div class="container mx-auto text-center px-4">
               <div class="flex justify-center mb-4 md:mb-8">
                  <img src="https://repository-images.githubusercontent.com/817622930/7e96d62f-3fbc-4c90-abd1-eba331f61291" alt="더영하나" class="mx-auto">
               </div>
               <h2 class="text-2xl md:text-3xl lg:text-4xl font-bold mb-2 md:mb-4">대학생을 위한 금융 생활 동반자</h2>
               <p class="text-base md:text-lg lg:text-xl">사회에 첫 발을 디딘 MZ세대 대학생들을 위한 맞춤형 금융 서비스</p>
            </div>
         </section>
         <div class="container mx-auto px-4 mb-8">
               <h2 class="text-xl md:text-2xl font-bold mb-4"> 📜 산출물</h2>
               <div class="container mx-auto px-4 mb-8">
                  <h3 class="text-xl md:text-2xl font-bold mb-4"><a href="https://www.erdcloud.com/d/FKxt2HowhXXy7RP5i">📃 ERD 설계</a></h3>
                  <div class="embed-responsive">
                    <img width="9072" alt="Untitled" src="https://github.com/the-young-hana/theYoungHana-backend/assets/76941500/553a4ae1-4f97-4c28-93d5-440acf024c45">
                  </div>
               </div>
               <div class="container mx-auto px-4 mb-8">
                  <h3 class="text-xl md:text-2xl font-bold mb-4">📃 API 설계</h3>
                  <div class="embed-responsive">
                     <img src="https://raw.githubusercontent.com/the-young-hana/theYoungHana-backend/fca24b339a1563a063131e7467c9e195dca245b8/src/main/resources/static/api/api.png" alt="API 설계">
                  </div>
               </div>
               <div class="container mx-auto px-4 mb-8">
                <h3 class="text-xl md:text-2xl font-bold mb-4">📃 시스템 구성</h3>
                <div class="embed-responsive">
                   <img src="https://github.com/the-young-hana/theYoungHana-backend/assets/76941500/c9eee3a7-82f0-49d5-b4fd-b42255aa0e73" alt="시스템 구성">
                </div>
             </div>
            </div>
            <div class="tables-sm container mx-auto px-4 mb-8">
               <h2 class="text-xl md:text-2xl font-bold mb-4">🧑‍🤝‍🧑 역할 분담</h2>
               <table class="table-auto w-full border-collapse">
                  <thead>
                     <tr>
                        <th class="px-4 py-2 border text-center">김백규</th>
                        <th class="px-4 py-2 border text-center">문혜영</th>
                        <th class="px-4 py-2 border text-center">이은수</th>
                     </tr>
                  </thead>
                  <tbody>
                     <tr>
                        <td class="px-4 py-2 border text-center">
                           <a href="https://github.com/pocj8ur4in">
                           <img src="https://avatars.githubusercontent.com/u/105341168?v=4" width="100" class="mx-auto">
                           </a>
                        </td>
                        <td class="px-4 py-2 border text-center">
                           <a href="https://github.com/mummhy0811">
                           <img src="https://avatars.githubusercontent.com/u/76941500?v=4" width="100" class="mx-auto">
                           </a>
                        </td>
                        <td class="px-4 py-2 border text-center">
                           <a href="https://github.com/EunSo0">
                           <img src="https://avatars.githubusercontent.com/u/101039358?v=4" width="100" class="mx-auto">
                           </a>
                        </td>
                     </tr>
                     <tr>
                        <td class="px-4 py-2 border text-center">Back</td>
                        <td class="px-4 py-2 border text-center">Back</td>
                        <td class="px-4 py-2 border text-center">Front</td>
                     </tr>
                  </tbody>
               </table>
               <table class="table-auto w-full border-collapse">
                  <thead>
                     <tr>
                        <th class="px-4 py-2 border text-center">임혜진</th>
                        <th class="px-4 py-2 border text-center">정재건</th>
                        <th class="px-4 py-2 border text-center">최지웅</th>
                     </tr>
                  </thead>
                  <tbody>
                     <tr>
                        <td class="px-4 py-2 border text-center">
                           <a href="https://github.com/hejin8307">
                           <img src="https://avatars.githubusercontent.com/u/31836035?v=4" width="100" class="mx-auto">
                           </a>
                        </td>
                        <td class="px-4 py-2 border text-center">
                           <a href="https://github.com/jungjaegun">
                           <img src="https://avatars.githubusercontent.com/u/96280969?v=4" width="100" class="mx-auto">
                           </a>
                        </td>
                        <td class="px-4 py-2 border text-center">
                           <a href="https://github.com/wldnd9904">
                           <img src="https://avatars.githubusercontent.com/u/74809873?v=4" width="100" class="mx-auto">
                           </a>
                        </td>
                     </tr>
                     <tr>
                        <td class="px-4 py-2 border text-center">Front·Back</td>
                        <td class="px-4 py-2 border text-center">Back</td>
                        <td class="px-4 py-2 border text-center">Front</td>
                     </tr>
                  </tbody>
               </table>
            </div>
      </main>
   </body>
</html>

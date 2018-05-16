# Cunning

<html>

<head>
<title>CUNNING</title>

<style>
body {
              background-color:f0fff0;
              font-family: 'Calabri', sans-serif;
      }

tr
{
  color:black;
  font-size:17px;
    padding: 15px;
    text-align: left;
border-left: 1px solid #ddd
}


table, tr, td, th {
    padding: 5px;
    text-align: center;
}

button
{
  border-radius:3px;
  padding:6px;
  font-size:15px;
  font-family: 'Calabri', sans-serif;
  height:30px;
  cursor:pointer;
  background-color:aaceeb;
}
</style>

</head>

<body>

English Outreach: 
<p hidden id="ENG1"> Hi, [NAME] here from Storyful news agency. Did you film this yourself? If so, would it be OK for our news clients to use this, with credit to you, as per storyful.com/clearance? Thank you.</p>
<p hidden id="ENG2"> [NAME] here from @storyful. Did you film this yourself? Would it be OK for our news clients to use this, with credit to you, as per storyful.com/clearance? </p>
<p hidden id="ENG3"> [NAME} here from @storyful. I am writing about this video here: [LINK]. Did you film this yourself? Would it be OK for our news clients to use this, with credit to you, as per storyful.com/clearance? </p>

<br>
<button onclick="copyToClipboard('#ENG1')">Generic outreach</button>
<button onclick="copyToClipboard('#ENG2')">Generic Twitter/Instagram outreach</button>
<button onclick="copyToClipboard('#ENG3')">Outreach with URL reference</button>

<hr>

<table>

<tr>

<th> Romance |</th>
<th> Middle East  |</th>
<th> Central and Eastern Europe  |</th>
<th> East Asia </th>
<th> | South and SE Asia </th>

</tr>

<tr>

<td> Spanish  </a> </td>
<td> <a href="#Arabic"> Arabic  </a> </td>
<td> German </td>
<td> <a href="#ChineseS"> Chinese (mainland) </a> </td>
<td>   <a href="#Burmese"> Burmese </a> </td>

</tr>

<tr>

<td> <a href="#French"> French </a> </td>
<td> Persian </td>
<td> <a href="#Russian"> Russian </a>  </td>
<td> <a href="#ChineseHK"> Chinese (HK & Taiwan) </td>
<td> Rohingya </td>

</tr>

<tr>

<td> <a href="#Portuguese-b"> Portuguese </a> </td>
<td> Hebrew </td>
<td> Ukrainian </td>
<td> Japanese </td>
<td> Filipino/Tagalog </td>

</tr>

<tr>

<td> Catalan </td>
<td> Turkish </td>
<td> Polish </td>
<td> Korean </td>
<td> Thai </td>

</tr>

<tr>

<td> <a href="#Italian"> Italian </a> </td>
<td> Kurdish </td>
<td> Greek </td>
<td> </td>
<td> Vietnamese </td>

</tr>

<tr>

<td> </td>
<td> </td>
<td> Bosnian </td>
<td> </td>
<td> Indonesian </td>

</tr>

<tr>

<td> </td>
<td> </td>
<td> Hungarian </td>
<td> </td>
<td> Bengali </td>

</tr>

<tr>

<td> </td>
<td> </td>
<td> </td>
<td> </td>
<td> Hindi </td>

</tr>


</table>

<script>

function copyToClipboard(element) {
  var $temp = $("<input>");
  $("body").append($temp);
  $temp.val($(element).text()).select();
  document.execCommand("copy");
  $temp.remove();
}

</script>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>

<hr> 
<br>

<h2> French </h2> <a name=French>

<p hidden id="FR1"> F </p>

<button onclick="copyToClipboard('#FR1')">IGNORE THIS BUTTON! DON'T EVEN LOOK AT IT!</button>

<hr>

<h2> Portuguese (Brazil) </h2> <a name=Portuguese-b>


<p hidden id="PB1">Olá, eu sou [NAME], um Jornalista da agência de notícias Storyful.</p>
<p hidden id="PB2">Eu me chamo [NAME] da @storyful agência de notícias</p>
<p hidden id="PB3">Você filmou isso</p>
<p hidden id="PB5">Você tirou essa foto? </p>
<p hidden id="PB6">Você tirou essas fotos?</p>
<p hidden id="PB7">Está tudo bem em usar esse conteúdo, através https://storyful.com/clearance-portuguese?</p>
<p hidden id="PB8">Você pode me dizer onde isso foi filmado?</p>
<p hidden id="PB8a">Você pode me dizer onde isso foi fotografado?</p>
<p hidden id="PB9">Você pode me dizer quando isso foi filmado? ?</p>
<p hidden id="PB10">Você pode me contar onde e como isso aconteceu?</p>
<p hidden id="PB11">Você pode me falar quem filmou isso?</p>
<p hidden id="PB12">Quem te mandou isso?</p>
<p hidden id="PB13">Você pode me contar onde você achou isso?</p>
<p hidden id="PB14">Apenas confirmando:</p>
<p hidden id="PB15">Você pode por favor me contatar nesse email [editor@storyful.com]</p>
<p hidden id="PB16">Voce tem algum video disso?</p>
<p hidden id="PB17">Obrigado.</p>
<p hidden id="PB18">Mais detalhes em storyful.com/clearance-portuguese </p>
<p hidden id="PB19">Eu estou escrevendo sobre esse video: [LINK] [LINK]</p>
<p hidden id="PB"> P </p>


<button onclick="copyToClipboard('#PB1')">I'm [NAME] from Storyful.</button>
<button onclick="copyToClipboard('#PB2')">I'm [NAME] from @storyful.</button>
<br>
<button onclick="copyToClipboard('#PB3')">Did you film this/these?</button>
<button onclick="copyToClipboard('#PB5')">Did you take this picture?</button>
<button onclick="copyToClipboard('#PB6')">Did you take these pictures?</button>
<br>
<button onclick="copyToClipboard('#PB7')">Clearance request</button>
<br>
<button onclick="copyToClipboard('#PB8')">Where was this (video) taken?</button>
<button onclick="copyToClipboard('#PB8a')">Where was this (photo) taken?</button>
<button onclick="copyToClipboard('#PB9')">When was this taken?</button>
<button onclick="copyToClipboard('#PB10')">Where and when did this happen?</button>
<br>
<button onclick="copyToClipboard('#PB11')">Who filmed this?</button>
<button onclick="copyToClipboard('#PB12')">Who sent you this?</button>
<button onclick="copyToClipboard('#PB13')">Where did you find this?</button>
<br>
<button onclick="copyToClipboard('#PB14')">Just to confirm:</button>
<button onclick="copyToClipboard('#PB15')">Please email me at editor@storyful.com</button>
<button onclick="copyToClipboard('#PB16')">Do you have any video of this?</button>
<button onclick="copyToClipboard('#PB17')">Thank you</button>
<button onclick="copyToClipboard('#PB18')">More details at https://storyful.com/clearance-portuguese </button>
<button onclick="copyToClipboard('#PB19')">I am writing about this video: [LINK]</button>
<br>

<hr>

<h2> Italian </h2> <a name=Italian>

<p hidden id="ESP1">Sono [NAME] lavoro per l'agenzia stampa Storyful </p>
<p hidden id="ESP2">Ciao, lavoro per l'agenzia di stampa @Storyful</p>
<p hidden id="ESP3">Ha filmato Lei questo video? </p>
<p hidden id="ESP4">Hai filmato tu questi [NEEDS LINK]</p>
<p hidden id="ESP5">Questa foto e' stata scattata da te?</p>
<p hidden id="ESP6">Queste foto sono state scattate da te?</p>
<p hidden id="ESP7">Sarebbe possibile utilizzare questo contenuto secondo questo contratto {storyful.com/clearance-italian}?</p>
<p hidden id="ESP8">Puo' dirmi dove e' stato scattato?</p>
<p hidden id="ESP9">Puo' dirmi dove e' stato filmato?</p>
<p hidden id="ESP10">Puoi darmi l'indirizzo preciso</p>
<p hidden id="ESP11">Puo' dirmi dove ha scattato la foto?</p>
<p hidden id="ESP12">Puo' dirmi dove ha filmato il video?</p>
<p hidden id="ESP13">Puoi dirmi dove e quando e' stato filmato? ..dove e quando e' stata scattata?</p>
<p hidden id="ESP14">Puoi dirmi chi ha filmato questo?</p>
<p hidden id="ESP15">Puo' dirmi chi glielo ha mandato?</p>
<p hidden id="ESP16">Puoi dirmi dove l'ha visto online?</p>
<p hidden id="ESP17">Per essere sicuri:</p>
<p hidden id="ESP18">Potrebbe contattarmi o scrivermi al seguente indirizzo email? Editor@storyful.com</p>
<p hidden id="ESP19">Ha qualche video dell'evento?</p>
<p hidden id="ESP20">La ringrazio</p>
<p hidden id="ESP21">Maggiori informazioni presso storyful.com/clearance-italian</p>
<p hidden id="ESP22">Sto scrivendo a proposito di questo video:</p>

<button onclick="copyToClipboard('#ESP1')">I'm [NAME] from Storyful...</button>
<button onclick="copyToClipboard('#ESP2')">I'm from @Storyful...</button>
<br>
<button onclick="copyToClipboard('#ESP3')">Did you film this?</button>
<button onclick="copyToClipboard('#ESP4')">Did you film these?</button>
<button onclick="copyToClipboard('#ESP5')">Did you take this picture?</button>
<button onclick="copyToClipboard('#ESP6')">Did you take these pictures?</button>
<br>
<button onclick="copyToClipboard('#ESP7')">Clearance request </button>
<br>
<button onclick="copyToClipboard('#ESP8')">Where was this photo was taken?</button>
<button onclick="copyToClipboard('#ESP9')">Where was this was filmed?</button>
<button onclick="copyToClipboard('#ESP10')">Can you tell me the precise street?</button>
<button onclick="copyToClipboard('#ESP11')">When was this photo was taken? </button>
<button onclick="copyToClipboard('#ESP12')">When was this video was filmed?</button>
<button onclick="copyToClipboard('#ESP13')">Where and when did this happen?</button>
<br>
<button onclick="copyToClipboard('#ESP14')">Can you tell me who filmed this?</button>
<button onclick="copyToClipboard('#ESP15')">Who sent you this?</button>
<button onclick="copyToClipboard('#ESP16')">Can you tell me where you found this?</button>
<br>
<button onclick="copyToClipboard('#ESP17')">Just to confirm:</button>
<button onclick="copyToClipboard('#ESP18')">Email me at editor@storyful.com</button>
<button onclick="copyToClipboard('#ESP19')">Do you have any video of this?</button>
<button onclick="copyToClipboard('#ESP20')">Thanks</button>
<button onclick="copyToClipboard('#ESP21')">More details at storyful.com/clearance-italian</button>
<button onclick="copyToClipboard('#ESP22')">I am writing about this video:</button>

<hr>

<h2> Arabic </h2> <a name=Arabic>

<hr>

<h2> Russian </h2> <a name=Russian>

<p hidden id="RU1">Здравствуйте, я [NAME], журналист с агентством Storyful.</p>
<p hidden id="RU2">Я [NAME] из новостным агентства @storyful.</p>
<p hidden id="RU3">Вы сняли это?</p>
<p hidden id="RU4">Вы сняли это?</p>
<p hidden id="RU5">Вы фотографировали это?</p>
<p hidden id="RU6">Вы фотографировали это?</p>
<p hidden id="RU7">Можно передать Ваш видео нашим клиентам, чтобы они могли показать в эфир c Вашем именем? (storyful.com/clearance-russian)</p>
<p hidden id="RU8">Можете вы сказать мне где это произошло?</p>
<p hidden id="RU9">Можете вы сказать мне, когда это произошло?</p>
<p hidden id="RU10">Можете вы сказать мне, где и когда это произошло?</p>
<p hidden id="RU11">Можете вы сказать мне, кто снял это?</p>
<p hidden id="RU12">Кто вам это прислал?</p>
<p hidden id="RU13">Можете вы сказать мне где вы это нашли?</p>
<p hidden id="RU14">Просто чтобы подтвердить:</p>
<p hidden id="RU15">Можете бы вы связаться со мной по адресу [editor@storyful.com]</p>
<p hidden id="RU16">У вас есть дополнительное видео этого случая?</p>
<p hidden id="RU17">Большое спасибо</p>
<p hidden id="RU18">Дополнительная информация: http://storyful.com/clearance-russian</p>
<p hidden id="RU19">Я пишу вам об этом видео: [LINK]</p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>
<p hidden id="RU"> R </p>

<button onclick="copyToClipboard('#RU1')">I'm [NAME] from Storyful.</button>
<button onclick="copyToClipboard('#RU2')">I'm [NAME] from @storyful.</button>
<br>
<button onclick="copyToClipboard('#RU3')">Did you film this?</button>
<button onclick="copyToClipboard('#RU4')">Did you film these?</button>
<button onclick="copyToClipboard('#RU5')">Did you take this picture?</button>
<button onclick="copyToClipboard('#RU6')">Did you take these pictures?</button>
<br>
<button onclick="copyToClipboard('#RU7')">Clearance request</button>
<br>
<button onclick="copyToClipboard('#RU8')">Where was this taken?</button>
<button onclick="copyToClipboard('#RU9')">When was this taken?</button>
<button onclick="copyToClipboard('#RU10')">Where and when did this happen?</button>
<br>
<button onclick="copyToClipboard('#RU11')">Who filmed this?</button>
<button onclick="copyToClipboard('#RU12')">Who sent you this?</button>
<button onclick="copyToClipboard('#RU13')">Where did you find this?</button>
<br>
<button onclick="copyToClipboard('#RU14')">Just to confirm:</button>
<button onclick="copyToClipboard('#RU15')">Please email me at editor@storyful.com</button>
<button onclick="copyToClipboard('#RU16')">Do you have any video of this?</button>
<button onclick="copyToClipboard('#RU17')">Thank you</button>
<button onclick="copyToClipboard('#RU18')">More details at storyful.com/clearance-Russian </button>
<button onclick="copyToClipboard('#RU19')">I am writing about this video:</button>
<br>

<hr>

<h2> Chinese (mainland) </h2> <a name=ChineseS>

<p hidden id="MM1">您好, 我是[NAME], 我是Storyful 新闻社的记者.</p>
<p hidden id="MM2">我是[NAME], @Storyful 新闻社的记者.</p>
<p hidden id="MM3">可否确认视频的版权是您所有?</p>
<p hidden id="MM4">请问这些都是您拍的吗？</p>
<p hidden id="MM5">请问这照片是您拍的吗？</p>
<p hidden id="MM6">请问这些照片都是您拍的吗？</p>
<p hidden id="MM7">我们能否使用或转载您的视频 (storyful.com/clearance-simplified-chinese) ?</p>
<p hidden id="MM8">请问这是在哪儿拍的？</p>
<p hidden id="MM9">请问这是何时拍的？</p>
<p hidden id="MM10">请问这是在何地, 何时发生的?</p>
<p hidden id="MM11">请问这是谁拍的?</p>
<p hidden id="MM12">请问这是谁发给您的?</p>
<p hidden id="MM13">请问这是在哪找到的?</p>
<p hidden id="MM14">想确认一下:</p>
<p hidden id="MM15">请跟我联络: editor@storyful.com</p>
<p hidden id="MM16">请问您有影片吗？</p>
<p hidden id="MM17">谢谢.</p>
<p hidden id="MM18">详情请参照 storyful.com/clearance-simplified-chinese.</p>
<p hidden id="MM19">我正在写有关这影片的报导: [LINK]</p>


<button onclick="copyToClipboard('#MM1')">I'm [NAME] from Storyful.</button>
<button onclick="copyToClipboard('#MM2')">I'm [NAME] from @storyful.</button>
<br>
<button onclick="copyToClipboard('#MM3')">Did you film this?</button>
<button onclick="copyToClipboard('#MM4')">Did you film these?</button>
<button onclick="copyToClipboard('#MM5')">Did you take this picture?</button>
<button onclick="copyToClipboard('#MM6')">Did you take these pictures?</button>
<br>
<button onclick="copyToClipboard('#MM7')">Clearance request</button>
<br>
<button onclick="copyToClipboard('#MM8')">Where was this taken?</button>
<button onclick="copyToClipboard('#MM9')">When was this taken?</button>
<button onclick="copyToClipboard('#MM10')">Where and when did this happen?</button>
<br>
<button onclick="copyToClipboard('#MM11')">Who filmed this?</button>
<button onclick="copyToClipboard('#MM12')">Who sent you this?</button>
<button onclick="copyToClipboard('#MM13')">Where did you find this?</button>
<br>
<button onclick="copyToClipboard('#MM14')">Just to confirm:</button>
<button onclick="copyToClipboard('#MM15')">Please email me at editor@storyful.com</button>
<button onclick="copyToClipboard('#MM16')">Do you have any video of this?</button>
<button onclick="copyToClipboard('#MM17')">Thank you</button>
<button onclick="copyToClipboard('#MM18')">More details at storyful.com/clearance-simplified-chinese </button>
<button onclick="copyToClipboard('#MM19')">I am writing about this video: [LINK]</button>
<br>

<hr>

<h2> Chinese (Hong Kong & Taiwan) </h2> <a name=ChineseHK>

<p hidden id="MM1">您好, 我是[NAME], 我是Storyful 新聞社的記者.</p>
<p hidden id="MM2">我是[NAME], @Storyful 新聞社的記者. </p>
<p hidden id="MM3">請問這是您拍的嗎?</p>
<p hidden id="MM4">請問這些都是您拍的嗎？</p>
<p hidden id="MM5">請問這照片是您拍的嗎？</p>
<p hidden id="MM6">請問這些照片都是您拍的嗎？</p>
<p hidden id="MM7">請問我們可以轉載您的影片或照片嗎?　詳情請參照 storyful.com/clearance-traditional-chinese?</p>
<p hidden id="MM8">請問這是在哪兒拍的？</p>
<p hidden id="MM9">請問這是何時拍的？ </p>
<p hidden id="MM10">請問這是在何地, 何時發生的?</p>
<p hidden id="MM11">請問這是誰拍的?</p>
<p hidden id="MM12">請問這是誰發給您的?</p>
<p hidden id="MM13">請問這是在哪找到的?</p>
<p hidden id="MM14">想確認一下::</p>
<p hidden id="MM15">請跟我聯絡: editor@storyful.com </p>
<p hidden id="MM16">請問您有影片嗎？</p>
<p hidden id="MM17">謝謝.</p>
<p hidden id="MM18">詳情請參照 storyful.com/clearance-traditional-chinese</p>
<p hidden id="MM19">我正在寫有關這影片的報導: [LINK] </p>
<p hidden id="MM"> ZW </p>
<p hidden id="MM"> ZW </p>



<button onclick="copyToClipboard('#MM1')">I'm [NAME] from Storyful.</button>
<button onclick="copyToClipboard('#MM2')">I'm [NAME] from @storyful.</button>
<br>
<button onclick="copyToClipboard('#MM3')">Did you film this?</button>
<button onclick="copyToClipboard('#MM4')">Did you film these?</button>
<button onclick="copyToClipboard('#MM5')">Did you take this picture?</button>
<button onclick="copyToClipboard('#MM6')">Did you take these pictures?</button>
<br>
<button onclick="copyToClipboard('#MM7')">Clearance request</button>
<br>
<button onclick="copyToClipboard('#MM8')">Where was this taken?</button>
<button onclick="copyToClipboard('#MM9')">When was this taken?</button>
<button onclick="copyToClipboard('#MM10')">Where and when did this happen?</button>
<br>
<button onclick="copyToClipboard('#MM11')">Who filmed this?</button>
<button onclick="copyToClipboard('#MM12')">Who sent you this?</button>
<button onclick="copyToClipboard('#MM13')">Where did you find this?</button>
<br>
<button onclick="copyToClipboard('#MM14')">Just to confirm:</button>
<button onclick="copyToClipboard('#MM15')">Please email me at editor@storyful.com</button>
<button onclick="copyToClipboard('#MM16')">Do you have any video of this?</button>
<button onclick="copyToClipboard('#MM17')">Thank you</button>
<button onclick="copyToClipboard('#MM18')">More details at storyful.com/clearance-traditional-chinese </button>
<button onclick="copyToClipboard('#MM19')">I am writing about this video: [LINK]</button>
<br>

<hr>

<h2> Burmese </h2> <a name=Burmese>

<p hidden id="BR1">မဂၤလာပါ..ကၽြန္ေတာ့္ နာမည္ [name] လို႔ေခၚပါတယ္. ကၽြန္ေတာက Storyful သတင္း႒ာနက သတင္းေထာက္တစ္ေယာက္ပါ။</p>
<button onclick="copyToClipboard('#BR1')"> SPEAKER IS MALE: Hello, I’m NAME, a journalist with Storyful news agency.</button>
<p hidden id="BR2">NOTE: မဂၤလာပါ. ကၽြန္မ နာမည္ [name] လို႔ေခၚပါတယ္. ကၽြန္မ က Storyful သတင္း႒ာနက သတင္းေထာက္တစ္ေယာက္ပါ။</p>
<button onclick="copyToClipboard('#BR2')"> SPEAKER IS FEMALE: Hello, I’m NAME, a journalist with Storyful news agency.</button>
<p hidden id="BR3">@Storyful သတင္း႒ာနက [name] ပါ။</p>
<button onclick="copyToClipboard('#BR3')">I'm NAME with @storyful...</button>
<br>
<p hidden id="BR4">ဒီဗီဒီယိုကို ကိုယ္တိုင္ရိုက္ယူခဲ့တာလား။</p>
<button onclick="copyToClipboard('#BR4')">Did you film this? </button>
<p hidden id="BR5">ဒီဗီဒီယိုေတြကို ကိုယ္တိုင္ရိုက္ကူးခဲ့တာလား။</p>
<button onclick="copyToClipboard('#BR5')">Did you film these? </button>
<p hidden id="BR6">ဒီဓာတ္ပုံကို ကိုယ္တိုက္ရိုက္ခဲ့တာလား။</p>
<button onclick="copyToClipboard('#BR6')">Did you take this picture?</button>
<p hidden id="BR7">ဒီဓာတ္ပုံေတြကို ကိုယ္တိုင္ရိုက္ခဲ့တာလား။</p>
<button onclick="copyToClipboard('#BR7')">Did you take these pictures? </button>
<p hidden id="BR8">[storyful.com/clearance] ကေဖာ္ျပခ်က္ေတြနဲ႔အညီ ဒီအခ်က္အလက္/ဗီဒီယိုေတြကို ယူသုံးလို႔ရမလား။</p>
<br>
<button onclick="copyToClipboard('#BR8')">Clearance request</button>
<p hidden id="BR9">ဒီဗီဒီယို ကို ဘယ္ေန႔ ဘယ္အခ်ိန္မွာ ရိုက္ခဲ့တာလဲ</p>
<br>
<button onclick="copyToClipboard('#BR9')">Can you tell me when this video was taken? </button>
<p hidden id="BR10">ဓာတ္ပုံ ကို ဘယ္ေန႔ ဘယ္အခ်ိန္မွာ ရိုက္ခဲ့တာလဲ</p>
<button onclick="copyToClipboard('#BR10')">Can you tell me when this photo was taken? </button>
<p hidden id="BR11">အခင္းျဖစ္ပြားတဲ့ ေနရာနဲ႔အခ်ိန္ကို ျပေပးလို႔ရမလား။</p>
<button onclick="copyToClipboard('#BR11')">Can you take me where and when this happened? </button>
<p hidden id="BR12">ဒီဗီဒီယိုကို ဘယ္သူရိုက္ကူးခဲ့တာလဲ။</p>
<br>
<button onclick="copyToClipboard('#BR12')">Can you tell me who filmed this? </button>
<p hidden id="BR13">ဘယ္သူ႔ဆီကရတာလဲ</p>
<button onclick="copyToClipboard('#BR13')">Who sent this to you</button>
<p hidden id="BR14">ဘယ္အခ်ိန္ကေတြ႔ရွိခဲ့တာလဲ။</p>
<button onclick="copyToClipboard('#BR14')">Can you tell me where you found this? </button>
<p hidden id="BR15">ဒီဟာနဲ႔ပက္သက္ျပီး ဗီဒီရိုဖိုင္မ်ား ရွိသလား။</p>
<button onclick="copyToClipboard('#BR15')"> Do you have any video of this?</button>
<br>
<p hidden id="BR99">ပိုျပီးေသခ်ာေအာင္လို႔ပါ။</p>
<button onclick="copyToClipboard('#BR99')">Just to confirm:</button>
<p hidden id="BR98">editor@storyful.com ကို သင့္email ကေနတဆင့္ ဆက္သြယ္ေပးႏိုင္မလား။</p>
<button onclick="copyToClipboard('#BR98')"Can you please contact me at [editor@storyful.com]</button>
<p hidden id="BR16">ေက်းဇူးတင္ပါတယ္။</p>
<button onclick="copyToClipboard('#BR16')">Thanks</button>
<p hidden id="BR17">အခ်က္အလက္အျပည့္အစုံကို storyful.com/clearance မွာဖတ္ၾကည့္လိုရပါတယ္။</p>
<button onclick="copyToClipboard('#BR17')">Thanks</button>
<p hidden id="BR18">အခ်က္အလက္အျပည့္အစုံကို storyful.com/clearance မွာဖတ္ၾကည့္လိုရပါတယ္။</p>
<button onclick="copyToClipboard('#BR18')">More details at storyful.com/clearance</button>
<p hidden id="BR19">ဒီဗီဒီရို ကိုေျပာတာပါ: [Link]</p>
<button onclick="copyToClipboard('#BR19')">I am writing about this video: [LINK]</button>
<p hidden id="BR">BR</p>
<button onclick="copyToClipboard('#BR')">E</button>



</body>

</html>

<script>
  import EmailControl from "../components/Forms/emailControl.svelte";
  import PasswordControl from "../components/Forms/passwordControl.svelte";
  import SubmitBtn from "../components/Forms/submitBtn.svelte";
  import TextareaControl from "../components/Forms/textareaControl.svelte";
</script>

<div class="content flex flex-col">
  <!-- svelte-ignore a11y-missing-content -->
  <div
    class="section-1 h-screen flex justify-center items-center gap-[40px] bg-[url('/backgroundPage.png')]"
  >
    <div>
      <h1 class="text-[47px] font-black leading-[110%] w-[565px]">
        Внедрите систему самообслуживания в свой ресторан
      </h1>
      <p class="font-menium text-[28px] w-[567px] mt-[50px]">
        Повышает выручку до 40%. Работает на лояльность гостей.
      </p>
      <button
        class="w-[377px] h-[80px] rounded-[20px] bg-red-700 text-white text-[28px] font-black mt-[27px] outline-none ring-[5px] ring-transparent focus:ring-red-100"
        >Подключить</button
      >
    </div>
    <div class="">
      <img src="iPhone14pro.png" alt="iPhone" />
    </div>
  </div>

  <div
    class="heading h-[68px] bg-black flex justify-center items-center text-white text-[35px] font-black"
  >
    Хотите подключить?
  </div>

  <div class="section-2 py-[50px] mb-[100px] flex flex-col justify-center items-center">
    <div class="text-[35px] font-black">
      <h1>Ваш e-mail</h1>
      <EmailControl />
      <h1>Сообщение</h1>
      <TextareaControl />
      <button class="bg-red-700 text-white w-[500px] h-[70px] rounded-[20px] mt-[25px]">Отправить</button>
    </div>
  </div>
</div>

<style>
</style>

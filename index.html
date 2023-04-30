$(document).ready(function() {
    $('#generate_gift').click(function() {
        $('#generate_gift').html('<span class="loader"></span>');
      // 创建发送到服务器的数据对象
      var dataToSend = '{"userInput":"My wife loves chocolate, moives and traveling"}';
      gen_gifts('https://gengift.chartech.workers.dev/', dataToSend);
    });
  });

  function gen_gifts(url, dataToSend) {
    // 发送 POST 请求
    $.ajax({
        type: 'POST', // 请求类型
        url: url, // 请求的 URL
        data: dataToSend, // 将数据对象转换为 JSON 格式
        contentType: 'application/json', // 发送的数据类型
        success: function(response) {
            var items_html = ''; // 用于存储渲染后的 HTML 字符串
            $.each(response.data, function(index, item) {
                // 将每个 JSON 对象转换为 HTML 元素
                items_html += build_item(item.title, item.reason);
            });
            gift_html = build_item_div(items_html)
            $('gift_items').html(gift_html)

            $('#generate_gift').html('<p>Generate</p>');

            $('#send_birthday').html(build_send_div());
        },
        error: function(xhr, status, error) {
          // 请求失败处理
          console.log('AJAX 请求失败: ' + status + ', ' + error);
        }
      });
  }


  function build_item(title, reason) {
    item_html = '<div class="w-full lg:w-1/2 flex flex-row justify-center p-3">'
    +'<div class="flex flex-col w-full max-w-lg transform overflow-hidden rounded-2xl bg-white text-left align-middle shadow-xl transition-all">'
    +'<div class="relative flex flex-row items-center justify-center w-full h-[200px]">'
    +'<div class="absolute right-8 top-8"><div class="heart-btn "><span class="heart cursor-pointer "></span></div></div>'
    +'<img alt="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==" sizes="100vw" '
    +'srcset="/_next/image?url=%2Fgift_back.jpg&amp;w=640&amp;q=75 640w, /_next/image?url=%2Fgift_back.jpg&amp;w=750&amp;q=75 750w, /_next/image?url=%2Fgift_back.jpg&amp;w=828&amp;q=75 828w, /_next/image?url=%2Fgift_back.jpg&amp;w=1080&amp;q=75 1080w, /_next/image?url=%2Fgift_back.jpg&amp;w=1200&amp;q=75 1200w, /_next/image?url=%2Fgift_back.jpg&amp;w=1920&amp;q=75 1920w, /_next/image?url=%2Fgift_back.jpg&amp;w=2048&amp;q=75 2048w, /_next/image?url=%2Fgift_back.jpg&amp;w=3840&amp;q=75 3840w" '
    +'src="/_next/image?url=%2Fgift_back.jpg&amp;w=3840&amp;q=75" decoding="async" data-nimg="fill" loading="lazy" style="position: absolute; height: 100%; width: 100%; inset: 0px; object-fit: contain; object-position: 50% 50%; color: transparent;">'
    +'</div><div class="flex-grow p-4 flex flex-col"><h3 class="text-lg font-medium leading-6 text-gray-900">'
    + title
    +'</h3><div class="mt-4 flex-grow"><p class="text-sm text-gray-500">'
    + reason
    +'</p></div><div class="mt-6 flex justify-end items-end h-full">'
    +'<button class="generate-button bg-rose-600 cursor-pointer w-min whitespace-nowrap  focus-visible:outline-white hover:bg-rose-500">'
    +'<div class="generate"><p>Get Item</p></div></button></div></div></div></div>'
    return item_html;
  }

  function build_item_div(items_html) {
    html = '<div class="output"><div class="mt-4 w-full flex flex-row flex-wrap justify-center">'
    html += items_html
    html +='</div></div>'
    return html;
  }
  

  function build_send_div() {
    html = '<div class="pb-20 text-center max-w-[600px] w-full bg-white rounded-2xl p-8 mt-[-40px]">'
            +'<div class="text-rose-400 text-[24px] font-semibold mb-4">That\'s too soon...remind me before their birthday</div>'
            +'<div class="text-[rgba(0,0,0,0.6)] py-4 font-semibold text-[20px]">&nbsp;We\'ll send you a reminder before your loved one\'s birthday, with 10 creative gift ideas! </div>'
            +'<div class="max-w-[450px]" style="margin: 0px auto;">'
            +'  <form class="md:bg-white md:rounded-full overflow-hidden md:flex md:flex-row md:justify-center md:gap-2 md:border-2">'
            +'    <div class="bg-white rounded-full overflow-hidden flex flex-row justify-center col block md:hidden">'
            +'      <select class="bg-white text-zinc-500 outline-none focus-within:border-none p-2 mr-2">'
            +'        <option value="default" disabled="" hidden="">Day</option><option value="1">1</option><option value="2">2</option><option value="3">3</option><option value="4">4</option><option value="5">5</option><option value="6">6</option><option value="7">7</option><option value="8">8</option><option value="9">9</option><option value="10">10</option><option value="11">11</option><option value="12">12</option><option value="13">13</option><option value="14">14</option><option value="15">15</option><option value="16">16</option><option value="17">17</option><option value="18">18</option><option value="19">19</option><option value="20">20</option><option value="21">21</option><option value="22">22</option><option value="23">23</option><option value="24">24</option><option value="25">25</option><option value="26">26</option><option value="27">27</option><option value="28">28</option><option value="29">29</option><option value="30">30</option><option value="31">31</option>'
            +'      </select>'
            +'      <select class="bg-white text-zinc-500 outline-none focus-within:border-none p-2 mr-2">'
            +'        <option value="default" disabled="" hidden="">Month</option><option value="Jan">Jan</option><option value="Feb">Feb</option><option value="Mar">Mar</option><option value="Apr">Apr</option><option value="May">May</option><option value="Jun">Jun</option><option value="Jul">Jul</option><option value="Aug">Aug</option><option value="Sep">Sep</option><option value="Oct">Oct</option><option value="Nov">Nov</option><option value="Dec">Dec</option></select></div><div class="bg-white rounded-full overflow-hidden flex flex-row justify-center col border-2 md:border-0"><input class="rounded-full w-full p-4 flex-grow bg-white text-black outline-none border-r-2 border-r-grey-200 focus-visible:border-white" placeholder="Your email" type="email" value=""><select class="bg-white text-zinc-500 outline-none focus-within:border-none p-2 mr-2 hidden md:block"><option value="default" disabled="" hidden="">Day</option><option value="1">1</option><option value="2">2</option><option value="3">3</option><option value="4">4</option><option value="5">5</option><option value="6">6</option><option value="7">7</option><option value="8">8</option><option value="9">9</option><option value="10">10</option><option value="11">11</option><option value="12">12</option><option value="13">13</option><option value="14">14</option><option value="15">15</option><option value="16">16</option><option value="17">17</option><option value="18">18</option><option value="19">19</option><option value="20">20</option><option value="21">21</option><option value="22">22</option><option value="23">23</option><option value="24">24</option><option value="25">25</option><option value="26">26</option><option value="27">27</option><option value="28">28</option><option value="29">29</option><option value="30">30</option><option value="31">31</option>'
            +'      </select>'
            +'      <select class="bg-white text-zinc-500 outline-none focus-within:border-none p-2 mr-2 hidden md:block">'
            +'        <option value="default" disabled="" hidden="">Month</option><option value="Jan">Jan</option><option value="Feb">Feb</option>'
            +'        <option value="Mar">Mar</option><option value="Apr">Apr</option><option value="May">May</option><option value="Jun">Jun</option><option value="Jul">Jul</option><option value="Aug">Aug</option><option value="Sep">Sep</option><option value="Oct">Oct</option><option value="Nov">Nov</option><option value="Dec">Dec</option>'
            +'      </select>'
            +'    </div>'
            +'    <button class="generate-button bg-rose-600 cursor-pointer w-full md:w-min whitespace-nowrap mt-4 md:m-0 focus-visible:outline-white hover:bg-rose-500">'
            +'      <div class="generate">'
            +'        <p>Send</p>'
            +'      </div>'
            +'    </button>'
            +'  </form>'
            +'</div>'
            +'</div>'
    return html;
  }

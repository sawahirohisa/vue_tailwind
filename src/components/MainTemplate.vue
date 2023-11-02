<template>
  <body>
    <div class="h-[100vh] flex bg-[#9e8137] flex-col">
      <div class="bg-white flex justify-between p-2 h-20">
        <h4 class="flex pl-5 items-center">チャット</h4>
        <div class="flex justify-center items-center pr-5">
          <svg width="52" height="49" viewBox="0 0 52 49" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M0 24.5C0 10.969 10.969 0 24.5 0H27.5C41.031 0 52 10.969 52 24.5C52 38.031 41.031 49 27.5 49H24.5C10.969 49 0 38.031 0 24.5Z"
              fill="#EAB308" />
            <path
              d="M16.3203 17.625H20.0859C20.9401 17.625 21.6615 17.7552 22.25 18.0156C22.8438 18.276 23.2943 18.6615 23.6016 19.1719C23.9141 19.6771 24.0703 20.2995 24.0703 21.0391C24.0703 21.5599 23.9635 22.0365 23.75 22.4688C23.5417 22.8958 23.2396 23.2604 22.8438 23.5625C22.4531 23.8594 21.9844 24.0807 21.4375 24.2266L21.0156 24.3906H17.4766L17.4609 23.1641H20.1328C20.6745 23.1641 21.125 23.0703 21.4844 22.8828C21.8438 22.6901 22.1146 22.4323 22.2969 22.1094C22.4792 21.7865 22.5703 21.4297 22.5703 21.0391C22.5703 20.6016 22.4844 20.2188 22.3125 19.8906C22.1406 19.5625 21.8698 19.3099 21.5 19.1328C21.1354 18.9505 20.6641 18.8594 20.0859 18.8594H17.8281V29H16.3203V17.625ZM22.9688 29L20.2031 23.8438L21.7734 23.8359L24.5781 28.9062V29H22.9688ZM30.3906 18.6328L26.625 29H25.0859L29.4219 17.625H30.4141L30.3906 18.6328ZM33.5469 29L29.7734 18.6328L29.75 17.625H30.7422L35.0938 29H33.5469ZM33.3516 24.7891V26.0234H26.9609V24.7891H33.3516Z"
              fill="white" />
          </svg>
        </div>
      </div>

      <div class="flex flex-row flex-1 h-[calc(100vh-80px)]">
        <div class="bg-white flex flex-col w-64 overflow-y-scroll">

          <input type="text" placeholder="検索" class="rounded-2xl m-2 p-3  border-gray-300 border-solid border-2 bg-white">
   
            

          <div class="flex-1 flex flex-col">

            <div class="flex bg-gray-300 ml-1 mr-1 p-px"></div>

            <div class="cursor-pointer flex p-2.5 hover:bg-gray-300">
              <div class="flex items-center p-2.5">
                <img class="w-12 h-12 rounded-full" src="https://via.placeholder.com/51x48" />
              </div>
              <div class="flex-1 flex flex-col justify-center">
                <div class="text-black text-lg font-sans not-italic font-normal leading-7">佐藤</div>
                <div class="text-gray-600 text-base font-sans not-italic font-normal leading-6">またね</div>
              </div>
            </div>

            <div class="p-px bg-gray-300 ml-1 mr-1"></div>

            <div class="cursor-pointer flex p-2.5 hover:bg-gray-300">
              <div class="flex items-center p-2.5">
                <img class="w-12 h-12 rounded-full" src="https://via.placeholder.com/51x48" />
              </div>
              <div class="flex-1 flex flex-col justify-center">
                <div class="text-black text-lg font-sans not-italic font-normal leading-7">鈴木</div>
                <div class="text-gray-600 text-base font-sans not-italic font-normal leading-6">おはよう</div>
              </div>
            </div>

            <div class="p-px bg-gray-300 ml-1 mr-1"></div>

            <div class="cursor-pointer flex p-2.5 hover:bg-gray-300">
              <div class="flex items-center p-2.5">
                <img class="w-12 h-12 rounded-full" src="https://via.placeholder.com/51x48" />
              </div>
              <div class="flex-1 flex flex-col justify-center">
                <div class="text-black font-sans text-lg not-italic font-normal leading-7">伊藤</div>
                <div class="text-gray-600 text-base font-sans not-italic font-normal leading-6">それは素晴らしい</div>
              </div>
            </div>

            <div class="p-px bg-gray-300 ml-1  mr-1"></div>

            <div class="cursor-pointer flex p-2.5 hover:bg-gray-300">
              <div class="flex items-center p-2.5">
                <img class="w-12 h-12 rounded-full" src="https://via.placeholder.com/51x48" />
              </div>
              <div class="flex-1 flex flex-col justify-center">
                <div class="text-black font-sans text-lg not-italic font-normal leading-7">山本</div>
                <div class="text-gray-600  font-sans text-base not-italic font-normal leading-6">また</div>
              </div>
            </div>

            <div class="p-px bg-gray-300 ml-1 mr-1"></div>

            <div class="cursor-pointer flex p-2.5 hover:bg-gray-300">
              <div class="flex items-center p-2.5">
                <img class="w-12 h-12 rounded-full" src="https://via.placeholder.com/51x48" />
              </div>
              <div class="flex-1 flex flex-col justify-center">
                <div class="text-black font-sans text-lg not-italic font-normal leading-7">中村</div>
                <div class="text-gray-600 font-sans text-base not-italic font-normal leading-6">また</div>
              </div>
            </div>

            <div class="p-px bg-gray-300 ml-1 mr-1"></div>

            <div class="cursor-pointer flex p-2.5 hover:bg-gray-300">
              <div class="flex items-center; p-2.5">
                <img class="w-12 h-12 rounded-full" src="https://via.placeholder.com/51x48" />
              </div>
              <div class="flex-1 flex flex-col justify-center">
                <div class="text-black font-sans text-lg not-italic font-normal leading-7">加藤</div>
                <div class="text-gray-600 font-sans text-base not-itaric font-normal leading-6">また</div>
              </div>
            </div>

            <div class="p-px bg-gray-300 ml-1 mr-1"></div>
          </div>



        </div>


        <div class="flex-1 bg-white flex flex-col h-[calc(100vh-80px)]">
          <div class="overflow-y-scroll flex p-2.5 flex-col flex-1">


            <div class="justify-end">
              <div class="flex p-1">
                <div class="flex-1 flex justify-end">
                  <div class="bg-blue-400 rounded-tr-xl rounded-bl-3xl rounded-tl-3xl  p-3 justify-center items-center">
                    <div class="text-white text-base font-normal font-sans break-words leading-6 items-center">
                      こんにちは！元気ですか？</div>
                  </div>
                </div>
                <div class="flex items-center p-2.5 justify-between">
                  <img class="w-8 h-8 rounded-full" src="https://via.placeholder.com/34x31" />
                </div>
              </div>
            </div>

            <div class="justify-end">
              <div class="flex p-1">
                <div class="flex items-center p-2.5 justify-between">
                  <img class="w-8 h-8 rounded-full" src="https://via.placeholder.com/34x31" />
                </div>
                <div class="flex-1 flex justify-start">
                  <div class="bg-gray-500 rounded-tl-xl rounded-tr-3xl  rounded-br-3xl p-2  justify-center items-center">
                    <div class="text-white text-base font-sans font-normal leading-6 break-words items-center">
                      こんにちは！元気だよ。最近新しい趣味を見つけて、ゆっくり楽しんでいます。最初は料理を習い始めました。料理は楽しくて創造的で、新しいレシピを試してみるのは楽しいです。君は何か新しいことを始めたことがありますか？
                    </div>
                  </div>
                </div>

              </div>
            </div>

            <div class="justify-end">
              <div class="flex p-1">
                <div class="flex-1 flex justify-end">
                  <div class="bg-blue-400 rounded-tr-xl rounded-bl-3xl rounded-tl-3xl p-3 justify-center items-center">
                    <div class="text-white text-base font-normal font-sans break-words leading-6 items-center">
                      それは素晴らしいですね！週末に何を計画していますか？</div>
                  </div>
                </div>
                <div class="flex items-center p-2.5 justify-between">
                  <img class="w-8 h-8 rounded-full" src="https://via.placeholder.com/34x31" />
                </div>
              </div>
            </div>

            <div class="justify-end">
              <div class="flex p-1">
                <div class="flex-1 flex justify-end">
                  <div class="bg-blue-400 rounded-tr-xl rounded-bl-3xl rounded-tl-3xl p-3 justify-center items-center">
                    <div class="text-white text-base font-normal font-sans break-words leading-6 items-center">
                      週末には映画を見に行くつもりです。君も一緒に来ない？</div>
                  </div>
                </div>
                <div class="flex items-center p-2.5 justify-between">
                  <img class="w-8 h-8 rounded-full" src="https://via.placeholder.com/34x31" />
                </div>
              </div>
            </div>


            <div class="justify-end">
              <div class="flex p-1">
                <div class="flex items-center p-2.5 justify-between">
                  <img class="w-8 h-8 rounded-full" src="https://via.placeholder.com/34x31" />
                </div>
                <div class="flex-1 flex justify-start">
                  <div class="bg-gray-500 rounded-tl-xl rounded-tr-3xl  rounded-br-3xl p-2  justify-center items-center ">
                    <div class=" text-white text-base font-normal font-sans break-words leading-6 items-center">
                      それは素晴らしいアイデアです！私も行きたい。</div>
                  </div>
                </div>

              </div>
            </div>

          </div>


          <div class="mt-1 mb-1 flex p-1 flex-row justify-end">
            <input type="text" placeholder="メッセージ" class="flex flex-1 text-gray-600 rounded-xl bg-[#eaeaea] p-3.5 m-2.5">

            <svg class="ml-1 mr-5 mt-2 cursor-pointer " width="59" height="59" viewBox="0 0 59 59" fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <path
                d="M29.5 31.9583L9.83329 19.6666V44.25H31.9583V49.1666H9.83329C8.48121 49.1666 7.32374 48.6852 6.3609 47.7224C5.39805 46.7595 4.91663 45.6021 4.91663 44.25V14.75C4.91663 13.3979 5.39805 12.2404 6.3609 11.2776C7.32374 10.3147 8.48121 9.83331 9.83329 9.83331H49.1666C50.5187 9.83331 51.6762 10.3147 52.639 11.2776C53.6019 12.2404 54.0833 13.3979 54.0833 14.75V31.9583H49.1666V19.6666L29.5 31.9583ZM29.5 27.0416L49.1666 14.75H9.83329L29.5 27.0416ZM46.7083 56.5416L43.2666 53.1L47.1385 49.1666H36.875V44.25H47.1385L43.2052 40.3166L46.7083 36.875L56.5416 46.7083L46.7083 56.5416ZM9.83329 19.6666V46.7083V31.9583V32.1427V14.75V19.6666Z"
                fill="#6F6F6F" />
            </svg>
          </div>

        </div>



        <div class="w-80 bg-white pl-2.5 flex  items-start overflow-y-scroll flex-col gap-[16px]">

          <div class="w-44 text-black text-lg font-sans font-normal leading-7 break-words">
            伊藤</div>
          <img class="w-64 rounded-xl" src="https://via.placeholder.com/272x257" />
          <div class="w-40 text-black text-lg font-sans font-normal leading-6">
            2021年9月22日に参加</div>
          <div class="w-52 text-black text-lg font-sans font-normal leading-6 break-words">
            こんにちは、伊藤です。趣味は音楽鑑賞、旅行、そして料理です。幼少期から音楽に興味を持ち、ピアノとギターを演奏することができます。</div>

        </div>
      </div>
    </div>
  </body>
</template>
  
<style scoped>
</style>
  
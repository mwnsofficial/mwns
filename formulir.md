---
title: "Formulir pembuka loker"
keywords: formulir
tags: [loker_banua]
sidebar: menu_loker
permalink: formulir.html
summary: Mengisi form untuk pengajuan lowongan kerja.
---
<div class="flex items-center min-h-screen bg-gray-50 dark:bg-gray-900">
  <div class="container mx-auto">
    <div class="max-w-md mx-auto my-10 bg-white p-5 rounded-md shadow-sm">
      <div class="text-center">
        <h1 class="my-3 text-3xl font-semibold text-gray-700 dark:text-gray-200">
          Form Data
        </h1>
        <p class="text-gray-400 dark:text-gray-400">
          Bagi anda yang ingin membuka lowongan kerja bisa kirimkan pesan ke admin.
        </p>
      </div>
      <div class="m-7">
        <form action="https://api.web3forms.com/submit" method="POST" id="form">
          <input type="hidden" name="access_key" value="9bd28744-e2d8-4326-8fe7-65cd7311714c" />
          <input type="hidden" name="subject" value="New Submission from Web3Forms" />
          <input type="checkbox" name="botcheck" id="" style="display: none;" />

          <div class="mb-6">
            <label for="name" class="block mb-2 text-sm text-gray-600 dark:text-gray-400">Nama Anda</label>
            <input type="text" name="name" id="name" placeholder="Contoh, Muhammad Yusuf" required class="w-full px-3 py-2 placeholder-gray-300 border border-gray-300 rounded-md focus:outline-none focus:ring focus:ring-indigo-100 focus:border-indigo-300 dark:bg-gray-700 dark:text-white dark:placeholder-gray-500 dark:border-gray-600 dark:focus:ring-gray-900 dark:focus:border-gray-500" />
          </div>
          <div class="mb-6">
            <label for="email" class="block mb-2 text-sm text-gray-600 dark:text-gray-400">Email Anda</label>
            <input type="email" name="email" id="email" placeholder="Contoh, master@mwns.my.id" required class="w-full px-3 py-2 placeholder-gray-300 border border-gray-300 rounded-md focus:outline-none focus:ring focus:ring-indigo-100 focus:border-indigo-300 dark:bg-gray-700 dark:text-white dark:placeholder-gray-500 dark:border-gray-600 dark:focus:ring-gray-900 dark:focus:border-gray-500" />
          </div>
          <div class="mb-6">
            <label for="phone" class="text-sm text-gray-600 dark:text-gray-400">No Telp</label>
            <input type="text" name="phone" id="phone" placeholder="0877-6424-1047" required class="w-full px-3 py-2 placeholder-gray-300 border border-gray-300 rounded-md focus:outline-none focus:ring focus:ring-indigo-100 focus:border-indigo-300 dark:bg-gray-700 dark:text-white dark:placeholder-gray-500 dark:border-gray-600 dark:focus:ring-gray-900 dark:focus:border-gray-500" />
          </div>
          <div class="mb-6">
          <label for="message" class="block mb-2 text-sm text-gray-600 dark:text-gray-400">Pesan Anda</label>
          
          <textarea rows="5" name="message" id="message" placeholder="Isi pesan...." class="w-full px-3 py-2 placeholder-gray-300 border border-gray-300 rounded-md focus:outline-none focus:ring focus:ring-indigo-100 focus:border-indigo-300 dark:bg-gray-700 dark:text-white dark:placeholder-gray-500 dark:border-gray-600 dark:focus:ring-gray-900 dark:focus:border-gray-500" required></textarea>
          </div>
          <div class="mb-6">
          <button type="submit" class="w-full px-3 py-4 text-white bg-indigo-500 rounded-md focus:bg-indigo-600 focus:outline-none">Kirim Pesan</button>
          </div>
          <p class="text-base text-center text-gray-400" id="result"></p>
        </form>
      </div>
    </div>
  </div>
</div>
<script src="/js/formdata.js"></script>

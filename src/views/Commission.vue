<template>
  <div class="commission">
    <img class="m-auto w-3/4" alt="Vue logo" src="../assets/comms.png">

    <div class="m-auto w-2/3 text-left">

        <div class="hidden sm:block" aria-hidden="true">
            <div class="py-5">
                <div class="border-t border-gray-200"></div>
            </div>
        </div>

        <div class="mt-10 sm:mt-0">
            <div class="md:grid md:grid-cols-3 md:gap-6">
                <div class="md:col-span-1">
                    <div class="px-4 sm:px-0">
                        <h3 class="text-lg font-medium leading-6 text-gray-900">Request a Commission</h3>
                        <p class="mt-1 text-sm text-gray-600">Describe what you have in mind using this form and I'll contact you as soon as I can.</p>
                    </div>
                </div>
                <div class="mt-5 md:mt-0 md:col-span-2">
                    <form action="#" method="POST">
                        <div class="shadow overflow-hidden sm:rounded-md">
                            <div class="px-4 py-5 bg-white sm:p-6">
                                <div class="grid grid-cols-6 gap-6">
                                    <div class="col-span-6 sm:col-span-3">
                                        <label for="first-name" class="block text-sm font-medium text-gray-700">First name</label>
                                        <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
                                    </div>

                                    <div class="col-span-6 sm:col-span-3">
                                        <label for="last-name" class="block text-sm font-medium text-gray-700">Last name</label>
                                        <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
                                    </div>

                                    <div class="col-span-6">
                                        <label for="email-address" class="block text-sm font-medium text-gray-700">Email address</label>
                                        <input type="text" name="email-address" id="email-address" autocomplete="email" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
                                    </div>

                                    <div class="col-span-6 sm:col-span-6">
                                        <fieldset>
                                            <div>
                                                <legend class="text-base font-medium text-gray-900">Character size</legend>
                                                <p class="text-sm text-gray-500">Price varies with size.</p>
                                            </div>
                                            <div class="mt-4 space-y-4">
                                                <div class="flex items-center">
                                                <input id="push-everything" name="push-notifications" type="radio" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300">
                                                <label for="push-everything" class="ml-3 block text-sm font-medium text-gray-700"> Portrait </label>
                                                </div>
                                                <div class="flex items-center">
                                                <input id="push-email" name="push-notifications" type="radio" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300">
                                                <label for="push-email" class="ml-3 block text-sm font-medium text-gray-700"> Half body </label>
                                                </div>
                                                <div class="flex items-center">
                                                <input id="push-nothing" name="push-notifications" type="radio" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300">
                                                <label for="push-nothing" class="ml-3 block text-sm font-medium text-gray-700"> Full height </label>
                                                </div>
                                            </div>
                                        </fieldset>
                                    </div>

                                    <div class="col-span-6 sm:col-span-6">
                                        <fieldset>
                                            <legend class="text-base font-medium text-gray-900">Add</legend>
                                            <div class="mt-4 space-y-4">
                                                <div class="flex items-start">
                                                <div class="flex items-center h-5">
                                                    <input id="comments" name="comments" type="checkbox" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300 rounded">
                                                </div>
                                                <div class="ml-3 text-sm">
                                                    <label for="comments" class="font-medium text-gray-700">Background</label>
                                                    <p class="text-gray-500">You can specify more details below or upload a reference photo.</p>
                                                </div>
                                                </div>
                                                <div class="flex items-start">
                                                <div class="flex items-center h-5">
                                                    <input id="candidates" name="candidates" type="checkbox" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300 rounded">
                                                </div>
                                                <div class="ml-3 text-sm">
                                                    <label for="candidates" class="font-medium text-gray-700">Custom details</label>
                                                    <p class="text-gray-500">You can specify more details below.</p>
                                                </div>
                                                </div>
                                
                                            </div>
                                        </fieldset>

                                    </div>



                                    <div class="col-span-6 sm:col-span-6">
                                        <label for="details" class="block text-sm font-medium text-gray-700"> Details </label>
                                        <div class="mt-1">
                                            <textarea id="details" name="details" rows="6" class="shadow-sm focus:ring-indigo-500 focus:border-indigo-500 mt-1 block w-full sm:text-sm border border-gray-300 rounded-md" placeholder="Your specifications."></textarea>
                                        </div>
                                        <p class="mt-2 text-sm text-gray-500">Don't hesitate to add some details.</p>
                                    </div>

                                    <div class="col-span-6 sm:col-span-6">
                                         <div>
                                            <label class="block text-sm font-medium text-gray-700"> Reference photos</label>
                                            <div class="mt-1 flex justify-center px-6 pt-5 pb-6 border-2 border-gray-300 border-dashed rounded-md">
                                                <div class="space-y-1 text-center">
                                                    <svg class="mx-auto h-12 w-12 text-gray-400" stroke="currentColor" fill="none" viewBox="0 0 48 48" aria-hidden="true">
                                                        <path d="M28 8H12a4 4 0 00-4 4v20m32-12v8m0 0v8a4 4 0 01-4 4H12a4 4 0 01-4-4v-4m32-4l-3.172-3.172a4 4 0 00-5.656 0L28 28M8 32l9.172-9.172a4 4 0 015.656 0L28 28m0 0l4 4m4-24h8m-4-4v8m-12 4h.02" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                                                    </svg>
                                                    <div class="flex text-sm text-gray-600">
                                                        <label for="file-upload" class="relative cursor-pointer bg-white rounded-md font-medium text-indigo-600 hover:text-indigo-500 focus-within:outline-none focus-within:ring-2 focus-within:ring-offset-2 focus-within:ring-indigo-500">
                                                        <span>Upload a file</span>
                                                        <input id="file-upload" name="file-upload" type="file" class="sr-only" multiple>
                                                        </label>
                                                        <p class="pl-1">or drag and drop</p>
                                                    </div>
                                                    <p class="text-xs text-gray-500">PNG, JPG, GIF up to 10MB</p>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="px-4 py-3 bg-gray-50 text-right sm:px-6">
                                <button type="submit" class="inline-flex justify-center py-2 px-4 border border-transparent shadow-sm text-sm font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">Send</button>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>

    </div>
    

    



  </div>
</template>

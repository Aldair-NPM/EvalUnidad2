<template>
            <div class="mt-12 flex flex-col items-center">
                <h1 class="text-2xl xl:text-3xl font-extrabold">
                    Registro
                </h1>
                <div class="w-full flex-1 mt-8 grid-cols-2">
                    <div class="grid grid-rows-2 grid-cols-2 gap-1">
                        <input
                            class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5 col-span-2"
                            type="text" placeholder="Nombre Completo" 
                        />
                        <input
                            class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5"
                            type="text" placeholder="Primer Apellido" 
                        />
                        <input
                            class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5"
                            type="text" placeholder="Segundo Apellido" 
                        />
                        <select id="countries" class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5">
                            <option selected>Genero</option>
                            <option value="M">Masculino</option>
                            <option value="F">Femenino</option>
                            <option value="NB">No Binario</option>
                        </select>
                        <select id="countries" class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5">
                            <option selected>Tipo de Sangre</option>
                            <option value="A+">A+</option>
                            <option value="A-">A-</option>
                            <option value="B+">B+</option>
                            <option value="B-">B-</option>
                            <option value="AB+">AB+</option>
                            <option value="AB-">AB-</option>
                            <option value="O+">O+</option>
                            <option value="O-">O-</option>
                        </select>
                        <input
                            class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5 col-span-2"
                            type="email" placeholder="Email" 
                        />
                        <input
                            class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5 "
                            type="password" placeholder="Contraseña" 
                        />
                        <input
                            class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5"
                            type="date" placeholder="Fecha de Nacimiento" 
                        />
                  
                        <label for="" class="font-medium col-span-2 ">Fotografia</label>
                        <input
                            class="w-full px-1 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-1 col-span-2"
                            type="file" placeholder="Fotografia"
                        />
                        <a href="/home">
                            <button
                                class="mt-5 tracking-wide font-semibold bg-green-700 text-gray-100 w-full py-4 rounded-lg hover:bg-green-900 transition-all duration-300 ease-in-out flex items-center justify-center focus:shadow-outline focus:outline-none col-span-2">
                                
                                <span>
                                    Sign Up
                                </span>
                            </button>
                        </a>
                        <a href="/"  >
                            <button
                                class="mt-5 tracking-wide font-semibold bg-red-700 text-gray-100 w-full py-4 rounded-lg hover:bg-red-900 transition-all duration-300 ease-in-out flex items-center justify-center focus:shadow-outline focus:outline-none col-span-2">
                                
                                <span>
                                    Cancel
                                </span>
                            </button>
                        </a>
                    </div>
                </div>
            </div>
</template>
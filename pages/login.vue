<template>
    <div class="container mx-auto p-4">
        <NuxtLink to="/">
            <img src="/img/svg/arrow_left_alt.svg" alt="">
        </NuxtLink>
        <div class="grid content-center">
            <img src="/img/logo.png" alt="" class="w-28 mx-auto mb-10 mt-6">
            <h3 class="font-bold text-3xl">Masuk</h3>
            <p class="text-sm italic">Masuk untuk mulai belajar di sini.</p>
    
            <div class="grid gap-6 mt-4">
                <FormsInput
                    label="Surat Elektronik"
                    type="email"
                    placeholder="Tuliskan Surat Elektronik"
                    id="surat-elektronik"
                />

                <FormsInput
                    label="Kata Sandi"
                    type="password"
                    placeholder="Tuliskan Kata Sandi"
                    id="kata-sandi"
                />
            </div>
            <a href="" class="block w-full text-right text-sm pr-2 mt-2 text-secondaryBlue">Lupa kata sandi</a>
            <a href="/dashboard" class="text-white block w-full text-center font-semibold p-4 bg-primaryBlue rounded-xl text-xl mt-4">Masuk</a>
        </div>
    </div>
</template>
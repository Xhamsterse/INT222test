<template>
    <div>
        <div class="overflow-hidden text-gray-600 body-font">
            <div class="container px-5 py-8 mx-auto bg-yellow-300 rounded-xl">
                <div class="flex flex-wrap mx-auto lg:w-4/5">
                    <img
                        alt="ecommerce"
                        class="object-cover object-center w-full h-64 rounded lg:w-1/2 lg:h-auto"
                        src="../assets/img/hilton_pattaya.jpg"
                    />
                    <div class="w-full mt-6 text-black lg:w-1/2 lg:pl-10 lg:py-6 lg:mt-0">
                        <h1 class="mb-1 text-4xl font-medium">Hilton Pattaya</h1>
                        <div class="text-xl leading-relaxed">
                            <p>ห้องพัก Deluxe one bedroom1 คืน สำหรับ 2 ท่าน</p>
                            <p>> สามารถนำสัตว์เลี้ยงมาได้</p>
                            <p>> ฟรี อาหารเช้า</p>
                            <p>> ฟรี อาหารเย็น</p>
                            <p>> ฟรี Mekha Pizza มูลค่า 420.-</p>
                            <p>สามารถใช้ได้ถึง 20/12/2021</p>
                            <p>จำนวน {2} ห้อง</p>
                            <br />
                            <p>ชื่อนามสกุลผู้ซื้อ: John Doe</p>
                            <p>Lind ID: JDoe</p>
                            <p>Email: jdoe99@hotmail.com</p>
                            <p>Tel: 0999999999</p>
                            <p>การชำระเงิน: Credit Card</p>
                        </div>
                    </div>
                </div>
            </div>
            <NuxtLink to="Confirm">
                <button
                    class="object-none object-right px-8 py-2 text-lg text-black bg-yellow-400 border-0 rounded-xl focus:outline-none hover:bg-yellow-300"
                >ยืนยันคำสั่งซื้อ</button>
            </NuxtLink>
        </div>
    </div>
</template>

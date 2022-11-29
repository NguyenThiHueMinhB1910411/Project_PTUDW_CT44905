<script>

import HeaderPublic from "../components/PublicHeader.vue";
import PublicFooters from "../components/PublicFooters.vue";

export default {
    components: {
        HeaderPublic, PublicFooters
    }
}
</script>
<template>
    <HeaderPublic />
   
    <main>
        <div class="d-flex justify-content-center container ">

            <table class="table table-hover table-bordered col-6 ">
                <thead>
                    <tr>
                        <th colspan="4 " class="text-light bg-form">Tin mới nhất</th>
                        <!-- <th scope="col">First</th>
                <th scope="col">Last</th>
                <th scope="col">Handle</th> -->
                    </tr>
                </thead>
                <tbody class="">
                    <tr>
                        <th scope="row"> 1</th>
                        <td colspan="3">Thông báo học bổng Cathay Life Insurance 2022</td>

                    </tr>
                    <tr>
                        <th scope="row"> 2</th>
                        <td colspan="3">Thông báo phát thẻ Bảo hiểm y tế và Bảo hiểm tai nạn cho sinh viên khóa 48</td>
                    </tr>
                    <tr>
                        <th scope="row"> 3</th>
                        <td colspan="3">Thông báo học bổng "Lương Định Của" năm học 2022 - 2023</td>
                    </tr>
                    <tr>
                        <th scope="row"> 4</th>
                        <td colspan="3">Quyết định hỗ trợ chi phí học tập học đợt ngày 07/11/2022</td>
                    </tr>
                    <tr>
                        <th scope="row"> 5</th>
                        <td colspan="3">Quyết định trợ cấp xã hội cho sinh viên đợt 15/11/2022</td>
                    </tr>
                </tbody>
            </table>
        </div>





    </main>
    <PublicFooters />

</template>

<style>
li {
    list-style: none;
}

.link {
    text-decoration: underline;
}

.bg-form {
    background-color: #3456b4;
}
</style>

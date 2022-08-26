<template>
     <div class="content">
        <div class="isi">
          <img src="src/assets/mrizki .jpeg" width="250" alt="">
        </div>

        <div class="text">
            <h2>Muhammad Rizki</h2>
            <table>
                            <thead>
                                <tr>
                                <th style="font-weight: bold;">Nama</th>
                                <th>:  Muhammad Rizki </th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td style="font-weight: bold;">Tempat,Tanggal Lahir</td>
                                    <td>:  Jakarta,27-November-2004</td>
                                </tr>
                                <tr>
                                    <td style="font-weight: bold;">Alamat</td>
                                    <td>:  Depok,Jawa Barat</td>
                                </tr>
                            </tbody>
                            <tfoot>
                                <tr>
                                    <td style="font-weight: bold;">No Handphone</td>
                                    <td>:  087880152514</td>
                                </tr>
                            </tfoot>
                </table>

                <p>
                    Perkenalkan nama saya Muhammad Rizki saya adalah seorang siswa kelas 12 yang bersekolah di SMK Taruna Bhakti Depok. Saya adalah Wab Developer saya juga punya ketertarikan dengan server yaitu backand.
                </p>
        </div>
            
     </div>
</template>

<style scoped>
    .content{
        display: flex ;
        /* margin: auto; */
        /* background-color: aqua; */
        /* width: 1000px; */
        border: solid;
        /* height: 400px; */
        box-shadow: 10px skyblue;
        /* margin-left: -100px; */
        width: 800px;
        margin: 50px 100px 20px 100px ;
        margin-top:50px ;
        /* background-color: aquamarine; */
    }

     /* .foto img{
        width: 200px;
        height: 200px;
    } */

    .text{
        padding-left: 70px;
    }

    .text h2{
        padding-bottom: 50px;
        /* padding-left: 100px; */
        text-decoration: underline;
        font-family:sans-serif ;
    }

    .text p {
        padding-top: 20px;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        font-weight: 400;
        text-transform: capitalize;
    }
  
</style>    
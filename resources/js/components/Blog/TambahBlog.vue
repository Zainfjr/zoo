<template>
<table class="table table-bordered">
                        <thead>                  
                          <tr>
                            <th>Nama</th>
                            <th style="width:25%" colspan="3"><center>Aksi</center></th>
                          </tr>
                        </thead>
                        <tr>
                          <td>asd</td>
                            <td>
                              <a  href="#">
                                <i class="fas fa-eye purple">Lihat</i>
                              </a>
                                <a href="#">
                                <i class="fas fa-edit green">|Edit|</i>
                              </a>
                                <a href="#">
                                    <i class="fas fa-trash-alt yellow">Hapus</i>
                                    </a>
                            </td>  
                        </tr>

                      </table>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
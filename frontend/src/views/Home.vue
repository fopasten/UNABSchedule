<template>
  <div class="home">
    <div class="row">
      <div class="col-sm-3">
        <div id="form_container" class="">
          <h3>Busqueda de cursos</h3>
          <form id="form" class="form-inline" method="post" action="">
            <div class="form-group row align-items-center">
              <label for="term" class="col-sm-3 col-form-label"
                >PERIODO:
              </label>
              <div class="col-sm-9">
                <select class="form-control" id="term">
                  <option>Default select</option>
                </select>
              </div>
            </div>
            <div class="form-group row align-items-center">
              <label for="course_code" class="col-sm-3 col-form-label"
                >SIGLA:
              </label>
              <div class="col-sm-9">
                <input
                  type="text"
                  class="form-control"
                  id="course_code"
                  placeholder="Ej. FMM028"
                />
              </div>
            </div>
            <div class="form-group row align-items-center">
              <label for="course_name" class="col-sm-3 col-form-label"
                >NOMBRE CURSO:
              </label>
              <div class="col-sm-9">
                <input
                  type="text"
                  class="form-control"
                  id="course_name"
                  placeholder="Ej. Matemática I"
                />
              </div>
            </div>
            <div class="form-group row align-items-center">
              <label for="course_nrc" class="col-sm-3 col-form-label"
                >NRC:
              </label>
              <div class="col-sm-9">
                <input
                  type="text"
                  class="form-control"
                  id="course_nrc"
                  placeholder="Ej. 1030"
                />
              </div>
            </div>
            <div class="form-group row align-items-center">
              <label for="campus" class="col-sm-3 col-form-label"
                >CAMPUS:
              </label>
              <div class="col-sm-9">
                <select class="form-control" id="campus">
                  <option value="" selected="selected"></option>
                  <option>ANT</option>
                  <option>BEL</option>
                  <option>CAS</option>
                  <option>CCR</option>
                  <option>CON</option>
                  <option>LLS</option>
                  <option>VIN</option>
                </select>
              </div>
            </div>

            <!-- <div class="form-group row align-items-center">

            </div> -->
            <div class="form-group row buttons">
              <!-- <input type="hidden" name="form_id" value="25966" /> -->

              <input
                id="saveForm"
                class="button_text col-sm-3"
                type="submit"
                name="submit"
                value="Submit"
              />
              <input type="reset" class="col-sm-3" />
            </div>
          </form>
        </div>
      </div>
      <div id="schedule" class="col-sm-8 align-items-center">
        <div style="padding: 5px">
          <table
            width="100%"
            cellpadding="0"
            cellspacing="0"
            border="0"
            style="border: 1px solid #ccd1e5; background: #fff"
          >
            <tbody>
              <tr>
                <td style="text-align: center; border: 1px solid #ccd1e5">
                  &nbsp;
                </td>
                <td style="text-align: center; border: 1px solid #ccd1e5">L</td>
                <td style="text-align: center; border: 1px solid #ccd1e5">M</td>
                <td style="text-align: center; border: 1px solid #ccd1e5">W</td>
                <td style="text-align: center; border: 1px solid #ccd1e5">J</td>
                <td style="text-align: center; border: 1px solid #ccd1e5">V</td>
                <td style="text-align: center; border: 1px solid #ccd1e5">S</td>
              </tr>
              <tr>
                <td
                  style="
                    text-align: center;
                    width: 20px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  08:30
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
              </tr>
              <tr>
                <td
                  style="
                    text-align: center;
                    width: 20px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  10:00
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
              </tr>
              <tr>
                <td
                  style="
                    text-align: center;
                    width: 20px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  11:30
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
              </tr>
              <tr>
                <td style="text-align: center; border: 1px solid #ccd1e5">
                  13:00
                </td>
                <td
                  colspan="6"
                  style="
                    background: #e7eaf6;
                    text-align: center;
                    border: 1px solid #ccd1e5;
                    letter-spacing: 30px;
                  "
                >
                  &nbsp;ALMUERZO
                </td>
              </tr>
              <tr>
                <td
                  style="
                    text-align: center;
                    width: 20px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  14:00
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
              </tr>
              <tr>
                <td
                  style="
                    text-align: center;
                    width: 20px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  15:30
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
              </tr>
              <tr>
                <td
                  style="
                    text-align: center;
                    width: 20px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  17:00
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
              </tr>
              <tr>
                <td
                  style="
                    text-align: center;
                    width: 20px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  18:30
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
              </tr>
              <tr>
                <td
                  style="
                    text-align: center;
                    width: 20px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  20:00
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
                <td
                  style="
                    text-align: center;
                    width: 60px;
                    border: 1px solid #ccd1e5;
                  "
                >
                  &nbsp;
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
    <div class="row">
      
    </div>

    <!-- <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "Home",
  components: {
    // HelloWorld
  },
};
</script>

<style scoped>
#form_container {
  padding: 20px 20px 20px 20px;
}
.form-group {
  padding: 2px 10px 2px 10px;
}

.form-group label {
  text-align: left;
}
</style>
<!-- pages/ImagePage.vue -->
<template>
  <q-page>
    <div class="q-pa-md row justify-center">
      <img
        alt="Example Image"
        src="~assets/logo_bolao.png"
        style="width: 600px; height: 600px"
      />
    </div>
    <div class="q-pa-md row justify-center">
      <div class="col-3">
        <q-btn
          push
          color="black"
          text-color="white"
          label="Selecione 15 Dezenas"
        />
      </div>
    </div>
    <div class="q-pa-md row justify-center">
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[0]"
          glossy
          text-color="white"
          @click="clickBotao(0)"
          >01</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[1]"
          glossy
          text-color="white"
          @click="clickBotao(1)"
          >02</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[2]"
          glossy
          text-color="white"
          @click="clickBotao(2)"
          >03</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[3]"
          glossy
          text-color="white"
          @click="clickBotao(3)"
          >04</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[4]"
          glossy
          text-color="white"
          @click="clickBotao(4)"
          >05</q-btn
        >
      </div>
    </div>
    <div class="q-pa-md row justify-center">
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[5]"
          glossy
          text-color="white"
          @click="clickBotao(5)"
          >06</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[6]"
          glossy
          text-color="white"
          @click="clickBotao(6)"
          >07</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[7]"
          glossy
          text-color="white"
          @click="clickBotao(7)"
          >08</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[8]"
          glossy
          text-color="white"
          @click="clickBotao(8)"
          >09</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[9]"
          glossy
          text-color="white"
          @click="clickBotao(9)"
          >10</q-btn
        >
      </div>
    </div>
    <div class="q-pa-md row justify-center">
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[10]"
          glossy
          text-color="white"
          @click="clickBotao(10)"
          >11</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[11]"
          glossy
          text-color="white"
          @click="clickBotao(11)"
          >12</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[12]"
          glossy
          text-color="white"
          @click="clickBotao(12)"
          >13</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[13]"
          glossy
          text-color="white"
          @click="clickBotao(13)"
          >14</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[14]"
          glossy
          text-color="white"
          @click="clickBotao(14)"
          >15</q-btn
        >
      </div>
    </div>
    <div class="q-pa-md row justify-center">
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[15]"
          glossy
          text-color="white"
          @click="clickBotao(15)"
          >16</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[16]"
          glossy
          text-color="white"
          @click="clickBotao(16)"
          >17</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[17]"
          glossy
          text-color="white"
          @click="clickBotao(17)"
          >18</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[18]"
          glossy
          text-color="white"
          @click="clickBotao(18)"
          >19</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[19]"
          glossy
          text-color="white"
          @click="clickBotao(19)"
          >20</q-btn
        >
      </div>
    </div>
    <div class="q-pa-md row justify-center">
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[20]"
          glossy
          text-color="white"
          @click="clickBotao(20)"
          >21</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[21]"
          glossy
          text-color="white"
          @click="clickBotao(21)"
          >22</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[22]"
          glossy
          text-color="white"
          @click="clickBotao(22)"
          >23</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[23]"
          glossy
          text-color="white"
          @click="clickBotao(23)"
          >24</q-btn
        >
      </div>
      <div class="col-2">
        <q-btn
          round
          :color="corBotao[24]"
          glossy
          text-color="white"
          @click="clickBotao(24)"
          >25</q-btn
        >
      </div>
    </div>
    <br />
    <div class="q-pa-md row justify-center">
      <div class="col-4">
        Quantidade de Números selecionados: <b>{{ qtdNumeros }}</b>
      </div>
    </div>
    <q-form @submit="registraParcipante" @reset="resetar" class="q-gutter-md">
      <div class="q-pa-md row justify-center">
        <div class="col-9">
          <q-input
            rounded
            outlined
            v-model="nomeParticipante"
            label="Informe aqui seu nome!"
            lazy-rules
            :rules="[
              (val) =>
                (val && val.length > 0) ||
                'Digite seu nome para poder se registrar !',
            ]"
          />
          <q-checkbox
            v-model="aceite"
            label="Eu quero ser milionário e me registrar no Bolão Mega Brothers da Loto Fácil de Independência"
            color="red"
          />
        </div>
      </div>
      <div class="q-pa-md row justify-center">
        <div class="col-3">
          <q-btn label="Registrar" type="submit" color="red" />
          <q-btn
            label="Resetar"
            type="reset"
            color="red"
            flat
            class="q-ml-sm"
          />
        </div>
      </div>
    </q-form>
  </q-page>
</template>
<script setup>
import axios from "axios";
import { ref } from "vue";
import { useRoute, useRouter } from "vue-router";
import { useQuasar } from "quasar";

const $q = useQuasar();

const route = useRoute();
const router = useRouter();
const nomeParticipante = ref(null);
const aceite = ref(false);
let numerosSelecionados = [];
var convite = route.query["convite"];
console.log(convite);

let qtdNumeros = 0;
const corBotao = ref([
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
  "red",
]);
const selecionado = [
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
  false,
];

validarConvite(convite);

function clickBotao(indice) {
  if (selecionado[indice] == false) {
    if (numerosSelecionados.length == 15) {
      $q.dialog({
        title: "CALMA CALABRESO!",
        message:
          "Você já selecionou 15 números! Deselecione um número para poder selecionar outro.",
      });
      return;
    }
    selecionado[indice] = true;
    corBotao.value[indice] = "green";
    qtdNumeros++;
    numerosSelecionados.push(indice + 1);
  } else {
    selecionado[indice] = false;
    corBotao.value[indice] = "red";
    qtdNumeros--;
    numerosSelecionados = numerosSelecionados.filter(function (item) {
      return item !== indice + 1;
    });
  }
}

function validarConvite(convite) {
  console.log(`URL DO BACKEND: ${process.env.URL_BACKEND}`);
  axios
    .get(`${process.env.URL_BACKEND}/convites/validar-convite?id=${convite}`)
    .then((response) => {
      if (!response.data.id_utilizado) {
        console.log("Convite is valid");
      } else {
        console.log("Convite is not valid");
      }
    })
    .catch((error) => {
      console.error("Error validating convite:", error);
      router.push({ path: "/convite-invalido" });
    });
}

function resetar() {}

function registraParcipante() {
  if (!aceite.value) {
    $q.dialog({
      title: "Alerta!",
      message:
        "Você precisa aceitar ser um milionário para se registrar. Clique no checkbox e tente novamente.",
    });
    return;
  }
  if (numerosSelecionados.length != 15) {
    $q.dialog({
      title: "Alerta!",
      message:
        "Selecione 15 números para poder se registrar. Nem Mais Nem Menos !",
    });
    return;
  }
  axios
    .post(`${process.env.URL_BACKEND}/participantes/registrar`, {
      nome_participante: nomeParticipante.value,
      convite: convite,
      numeros_selecionados: numerosSelecionados.toString(),
    })
    .then((response) => {
      console.log(response.data);
      router.push({ path: "/registrado" });
    })
    .catch((error) => {
      console.error("Error registering participant:", error);
      $q.dialog({
        title: "Erro!",
        message:
          "Erro ao se registrar. Tente novamente mais tarde. (" + error + ")",
      });
    });
}
</script>

<template>
  <div>
    유저의 선택
    <button v-on:click.once="btn01" v-show="show_sci">✌</button>
    <button v-on:click.once="btn02" v-show="show_rock">✊</button>
    <button v-on:click.once="btn03" v-show="show_papper">🖐</button>
  </div>

  <br />

  <div>
    컴퓨터의
    <button v-on:click.once="com01">선택</button>
    <div id="com02">{{ randNum }}</div>
  </div>

  <br />

  <div>{{ calculate() }}</div>

  <br />

  <button @click="btn04">다시하기</button>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      state_num: -1,
      show_sci: true,
      show_rock: true,
      show_papper: true,
      myChoice: 0,
      randNum: '대기중',
    };
  },
  methods: {
    com01: function () {
      let randNumber = Math.floor(Math.random() * 3);
      if (randNumber == 0) this.randNum = '✌';
      else if (randNumber == 1) this.randNum = '✊';
      else if (randNumber == 2) this.randNum = '🖐';
      this.state_num = randNumber;
    },
    btn01: function () {
      alert('가위');
      this.myChoice = 0;
      this.show_rock = !this.show_rock;
      this.show_papper = !this.show_papper;
    },
    btn02: function () {
      alert('바위');
      this.myChoice = 1;
      this.show_sci = !this.show_sci;
      this.show_papper = !this.show_papper;
    },
    btn03: function () {
      alert('보');
      this.myChoice = 2;
      this.show_sci = !this.show_sci;
      this.show_rock = !this.show_rock;
    },

    calculate: function () {
      if (this.myChoice == this.state_num) return '결과 : 비겼습니다.';
      else if (
        (this.myChoice == 0 && this.state_num == 2) ||
        (this.myChoice == 1 && this.state_num == 0) ||
        (this.myChoice == 2 && this.state_num == 1)
      )
        return '결과 : 이겼습니다';
      else if (
        (this.myChoice == 2 && this.state_num == 0) ||
        (this.myChoice == 0 && this.state_num == 1) ||
        (this.myChoice == 1 && this.state_num == 2)
      )
        return '결과 : 졌습니다';
    },

    btn04: function () {
      window.location.reload();
    },
  },
};
</script>

<script lang="ts">
    export let text : string;
    export let onClick: (value: string) =>void;
    export let color: 'orange' | 'grey' | 'dark-grey';
</script>

<div class="Button" text="1" onClick={()=>onClick{text}} color="orange">{text}</div>

<style lang="scss"></style>

// 버튼을 만들 때 무엇이 필요한가?
// 문자, 색상, 클릭이벤트, 문구

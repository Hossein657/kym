<template>
    <div class="container">
        <div class="info">
            <img src="~/static/test/pic.jpeg" alt="cover" class="cover">
            <div>
            <p class="title">The monster</p>
            <p class="artist">Eminem ft. Rihana</p>
            </div>
        </div>
        <div class="lyrics">
            [Intro: Rihanna]
I'm friends with the monster that's under my bed
Get along with the voices inside of my head
You're tryin' to save me, stop holdin' your breath
And you think I'm crazy, yeah, you think I'm crazy

[Verse 1: Eminem]
I wanted the fame but not the cover of Newsweek
Oh well, guess beggars can't be choosey
[Intro: Rihanna]
I'm friends with the monster that's under my bed
Get along with the voices inside of my head
You're tryin' to save me, stop holdin' your breath
And you think I'm crazy, yeah, you think I'm crazy

[Verse 1: Eminem]
I wanted the fame but not the cover of Newsweek
Oh well, guess beggars can't be choosey
[Intro: Rihanna]
I'm friends with the monster that's under my bed
Get along with the voices inside of my head
You're tryin' to save me, stop holdin' your breath
And you think I'm crazy, yeah, you think I'm crazy
[Verse 1: Eminem]
I wanted the fame but not the cover of Newsweek
Oh well, guess beggars can't be choosey
[Intro: Rihanna]
I'm friends with the monster that's under my bed
Get along with the voices inside of my head
You're tryin' to save me, stop holdin' your breath
And you think I'm crazy, yeah, you think I'm crazy

[Verse 1: Eminem]
I wanted the fame but not the cover of Newsweek
Oh well, guess beggars can't be choosey
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.container {
    padding: 20px;
    background-image: linear-gradient(to bottom, #fb531c, #f98c29);
    border-radius: 20px;
}
.info{
    display: flex;
    color: #efefef;
    margin-bottom: 20px;
}
.title{
    font-size: 20px;
    font-weight: 500;
}
.cover{
    width: 50px;
    height: 50px;
    border-radius: 10px;
    margin-right: 10px;
}
.lyrics{
    max-height: 50vh;
    overflow: scroll;
    color: #fff;
    padding-right: 25px;
}
</style>
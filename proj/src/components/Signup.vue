<template>
    <img src="../assets/logo.png" alt="alt logo">
    <h1>Sign Up</h1>
    <div class="inputfield"> <input type="text" for=" username" placeholder="Username">
        <input type="text" for="email" placeholder="Email">
        <input type="text" for="password" placeholder="Password">
    </div>
    <button class="flex items-center bg-blue-500 px-4 py-3 text-white hover:bg-blue-400">Sign Up</button>
</template>
<script>

export default {
    name: 'SignUp',
}

</script>
<style scoped>
img {
    width: 100px;
    height: 100px;

}

.inputfield {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 20px;
    border: 1px solid #cfc7c7;
    border-radius: 10px;
    max-width: 400px;
    margin: 10px auto;

    box-shadow: 0 0 10px rgba(0, 0, 0, 0)
}

.inputfield input {
    padding: 10px;
    margin: 10px;
    border: none;
    border-radius: 10px;
    width: 100%;
    height: 40px;
    padding: 20px;
    box-sizing: border-box;
}

button {
    padding: 10px;
    max-width: 400px;
    margin: 10px auto;
    border: none;
    border-radius: 10px;
    width: 100%;
}
</style>

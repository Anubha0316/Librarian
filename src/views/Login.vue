<template>
    <div class="center">
        <v-row>
            <v-col cols="10" offset="1" sm="3" offset-md="4" offset-lg="3">
                <v-avatar color="primary" size="95" tile>
                    <v-img src="@/assets/logo.png"></v-img>
                </v-avatar>
                <v-text-field label="Username"></v-text-field>
                <v-text-field label="Password" type="password"></v-text-field>
                <v-btn class="base-inverted" block @click="authenticate()">
                    Login
                </v-btn>
            </v-col>
        </v-row>
        <!-- <h1>Crazy Abubha Page</h1> -->
    </div>
</template>

<script>
export default {
    data() {
        return {
            username: "",
            password: ""
        }
    },
    methods: {
        authenticate() {
            alert("Login Successful");
        }
    },
}
</script>

<style lang="scss" scoped></style>
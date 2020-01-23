<template>
    <v-stepper
    v-model="currentStep">
        <v-stepper-header>
            <v-stepper-step :complete="currentStep > 1" step="1">Shipping</v-stepper-step>
            <v-divider></v-divider>
            <v-stepper-step :complete="currentStep > 2" step="2">payment</v-stepper-step>
            <v-divider></v-divider>
            <v-stepper-step step="3">place Order</v-stepper-step>
        </v-stepper-header>
        <v-stepper-items>
                <v-stepper-content step="1">
                    <v-card>
                        <h1>shipping step</h1>
                    </v-card>
                    <v-btn
                    color="primary"
                    @click="currentStep = 2">
                    continue
                    </v-btn>
                </v-stepper-content>
                <v-stepper-content step="2">
                    <v-card>
                        <h1>Payment step</h1>
                    </v-card>
                    <v-btn
                    color="primary"
                    @click="currentStep = 3">
                    continue
                    </v-btn>
                </v-stepper-content>
                <v-stepper-content step="3">
                    <v-card>
                        <h1>Place order step</h1>
                    </v-card>
                    <v-btn
                    color="primary"
                    @click="currentStep = 1">
                    continue
                    </v-btn>
                </v-stepper-content>
            </v-stepper-items>
    </v-stepper>
</template>

<script>
export default {
name:'checkout',
data : () =>({
    currentStep:0
}),
}
</script>

<style>

</style>

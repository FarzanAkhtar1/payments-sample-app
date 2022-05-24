<template>
  <v-layout>
    <v-flex>
      <v-card class="body-1 px-6 py-8 mb-4" max-width="800" outlined>
        <h1 class="headline">Fiat-To-USDC Onboarding application</h1>

        <body-2><font size="-1">This application has been modified from a base program. Please reach out to Farzan Akhtar (Twitter: @AkhtarFarzan1) regarding any questions or concerns</font></body-2>
        <p class="mt-6">
          This application is a Proof-Of-Concept of the implementaiton fo a system that will enable the conversion of Fiat to USDC stablecoin on Algorand in a 1:1 ratio, minus any fees.
        </p>
        <p class="mt-6">
          Any payment information provided in this application should not reflect your personal details. <b>Demo payment data will be supplied.</b> In addition, any card payments are simulated and there is no trasnfer of actual funds.
        </p>       
        <p class="mt-6">
          All transfers of digital assets, in particular USDC (on Algorand) is settled on the Algorand Testnet, which is a dedicated testing and development environments. Assets here have no monetary value.
        </p>         
        


      </v-card>

      <v-card class="body-1 px-6 py-8 mb-4" max-width="800" outlined>
        <h2 class="title">Getting Started</h2>
        <p class="font-weight-bold mt-8">We suggest you have the following:</p>

        <ul>
          <li>An Algorand Testnet wallet</li>
          <li>Some Algo to opt-in to USDC (ASA ID: 10458941) - A faucet is available <a href="https://dispenser.testnet.aws.algodev.network/"> here </a></li>
        </ul>
      
        <p>
          <v-btn href="/flow/charge" color="primary"> Let's go </v-btn>
        </p>

      </v-card>
    </v-flex>
  </v-layout>
</template>

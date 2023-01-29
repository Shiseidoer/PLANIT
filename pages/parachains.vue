<template>
  <div>
    <h1 class="mt-4">Parachains of Kusama</h1>

    <v-simple-table dense class="mt-4">
      <template v-slot:default>
        <thead>
          <tr>
            <th class="text-left">Names</th>
            <th class="text-left">Symbol</th>
            <th class="text-left">Type</th>
            <th class="text-left">Link</th>
            <th class="text-left">Rewards</th>
          </tr>
        </thead>
        <tbody class="grey--text mb-2">
          <tr v-for="item in desserts" :key="item.name">
            <td>{{ item.name }}</td>
            <td>{{ item.symbol }}</td>
            <td>{{ item.type }}</td>
            <td>{{ item.link }}</td>
            <td>{{ item.rewards }}</td>
          </tr>
        </tbody>
      </template>
   
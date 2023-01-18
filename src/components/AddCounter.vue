// AddCounter.vue

import Vue from 'vue';
import Vuex from 'vuex';
Vue.use(Vuex);

const store = new Vuex.Store({
  state: {
    count: 0
  },
  mutations: {
    increment (state, payload){
      return state.count = state.count + payload.amount;
    }
  },
  actions: {
    increment (context, payload) {
      context.commit('increment', payload)
  }
})
export default store;
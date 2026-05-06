import { createStore } from 'redux';
import cartReducer from './cartReducer';
import { composeWithDevTools } from '@redux-devtools/extension';

// Crie a Store e associe o reducer com Redux DevTools
const store = createStore(cartReducer, composeWithDevTools());

export default store;

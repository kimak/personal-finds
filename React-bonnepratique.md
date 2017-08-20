# Bonne pratique React/Redux


- JSX:
  - Mettre des commentaires /**/
  - Mettre des conditions:   {!!accountName &&
 +          <Text style={styles.account}>
 +            {accountName}
 +          </Text>}

- Container vs Components
	-> Bénéfice: permet de découpler la logique d'affichage du "métier"

- High Order Component
  - compose valilla javascript:

	- Bénéfice: Réutilisation de code = pas de duplication
	- Example: withLoading, withError

- Utiliser un maximum de composant stateless.


- Bonne pratique autour de React, Redux, ReactNative et les tests unitaire
http://kimak.react-slides.surge.sh/
Ce sont mes slides que j'utilise pour des élèves qui débutent.

- Architecture redux
https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0

- React Native Debugger
https://github.com/jhen0409/react-native-debugger

- Jest
https://facebook.github.io/jest/blog/2016/07/27/jest-14.html

- Gestion des styles avec StyledComponent
https://medium.com/seek-blog/a-unified-styling-language-d0c208de2660

- Navigation
https://reactnavigation.org/

- Gestion des icons en custom svg plutôt que react-native-vector-icons
https://github.com/react-native-community/react-native-svg

- Un middleware redux pour les appels network:
https://www.npmjs.com/package/fetch-redux-middleware

- Meilleur performance des animations avec useNativeDriver
https://facebook.github.io/react-native/blog/2017/02/14/using-native-driver-for-animated.html

- Async/await
http://facebook.github.io/react-native/releases/0.46/docs/network.html

- Redux-saga

Bonus:

- Animation exporter depuis AfterEffect pour un effet whaouh:
https://github.com/airbnb/lottie-react-native



TOOLING:

- pre-commit
https://github.com/observing/pre-commit



## Util

- redux-persist
- redux-offline

----------------------------
HOC Lifecycle

import React, { Component } from 'react';
import PropTypes from 'prop-types';

/* fetch('api/todos.json')
.then((response) =>  {
    return response.json();
}).then((results) => {
    this.props.fetchComplete(results);
}).catch((err) =>  {
    this.props.fetchError(err);
});*/
const withLifecycle = WrappedComponent => {
  class Lifecycle extends Component {
    componentDidMount() {
      if (this.props.didMount) {
        this.props.didMount();
      
    }
    componentWillMount() {

    }
    render() {
      return <WrappedComponent {...this.props} />;
    }
  }
  Lifecycle.propTypes = {
    didMount: PropTypes.func,
  };
  Lifecycle.defaultProps = {
    didMount: undefined,
  };
  return Lifecycle;
};

export default withLifecycle;



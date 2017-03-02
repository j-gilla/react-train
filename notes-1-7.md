
//Passed props for presentational component to render

//   render() {
//     return <Button>I <Heart />React</Button>
//   }
// }
//
// const Button = (props) => <button>{props.children}</button> //passed props for presentational component to render
//
// class Heart extends React.Component {
//   render() {
//     return <span>&hearts;</span>
//   }

//Passing state using children
//
//
// class App extends React.Component {
//   constructor(){
//     super(); //gives this context within component rather than parent class - App Extends
//       this.state = {
//         txt: 'this is the state text',
//         cat: 0
//       }
//   }
//   update( e ){
//     this.setState({txt: e.target.value})
//   }
//   render(){
//     return (
//       <div>
//         <h1>{this.state.txt}</h1>
//         <Widget update={this.update.bind(this)} />
//         <Widget update={this.update.bind(this)} />
//         <Widget update={this.update.bind(this)} />
//       </div>
//     )
//   }
// }
//
// const Widget = (props) =>
//   <input type="text" onChange={props.update} />


// Managing State with setState
//
// constructor(){
//   super(); //gives this context within component rather than parent class - App Extends
//     this.state = {
//       txt: 'this is the state text',
//       cat: 0
//     }
// }
// update( e ){
//   this.setState({txt: e.target.value})
// }
// render(){
//   return (
//     <div>
//       <input type="text" onChange={this.update.bind(this)} />
//       <h1>{this.state.txt}</h1>
//     </div>
// //only values definied in state are updated - anything inside the div will render
//   )
// }



// //Prop Types - Props
// App.propTypes ={
//   txt: React.PropTypes.string,
//   cat: React.PropTypes.number.isRequired
// }
//
// App.defaultProps = {
//   txt: "this is the default txt"
// }

// const Ap = () => <h1>Hello Stateless / Presentational</h1>

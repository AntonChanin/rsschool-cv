# 1. Anton Hanin 
# 2. Contact information:
## contact mail:
[antonchaninvl@gmail.com](https://mail.google.com/mail/u/0/?pli=1#inbox)
## contact phone:
 79168232949
# 3. Summary: 
My goal is to find a job that will not only immerse me in the exciting and progressive world of IT, but also provide a good financial position and prestige.  I would like this work to provide an opportunity for self-development in the field of IT and related areas associated with the development of their creative potential, internal and external discipline and technical skills.
# 4. Skills:
 * pascal
 * delphi 7
 * js
 * jquery
 * css
 * html
 * git
 * bitbucket
 * joomle 
 * react
 * redux
 * java
# 5. Code example:
``` import React, {Component} from 'react';
	import { connect } from 'react-redux';
	import { fetchDolls } from '../../redux/dolls/actions.js';
	//Components
	import Search from './editModal.js';
	import DollsList from './DollsList.js';
	const mapStateToProps = ({ dolls }) => ({ dolls });
	const mapDispatchToProps = dispatch => {
	  return {
	// dispatching actions returned by action creators
	   fetchDolls: () => dispatch(fetchDolls())
	  }
	};
	class CatalogueCom extends Component {
	  constructor(props) {
		super(props);
		this.state = {
		  searchValue: null
		}
	  }
	  componentDidMount() {
		const dollsInCatalogue =  this.fetchDolls();
		console.log('dollsInCatalogue', dollsInCatalogue);
	  }
	  async fetchDolls() {
		return await this.props.fetchDolls();
	  }
	  render() {
		console.log('current props Catalogue', this.props);
		return (
		  <div className="cont-pad">
			<Search type="text" categoryThis={this} />
			<div className="scroll-cataloge">
			  <DollsList dolls={[]} searchValue={this.state.searchValue}/>
			</div>
		  </div>
		)
	  }
	}
	export default connect (
	  mapStateToProps,
	  mapDispatchToProps
	)(CatalogueCom);
```
# 6. Experience:
* Graduation thesis: Development of the client part of the unified authentication and authorization system for the unified information and educational environment (front-end)
* Industrial practice in EPAM
# 7. Education:
* secondary school
* SP branch of VGIK secondary vocational education. qualification technician-programmer
* Udemy courses:
*
  [Web Development By Doing: HTML / CSS](https://www.udemy.com/certificate/UC-9BA2HGB5/?utm_campaign=email&utm_source=sendgrid.com&utm_medium=email)
*
  [Foundations of Front-End Web Development](https://www.udemy.com/certificate/UC-97KYO95J/)
*  
  [Master the Basics of HTML5 & CSS3: Beginner Web Development](https://www.udemy.com/certificate/UC-WOEBP1DV/)
# 8. English: 
* school classes
* as well as classes in this discipline in St. Petersburg branch of VGIK
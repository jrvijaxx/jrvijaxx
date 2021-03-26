import { JR.VIJAXX, Bio } from "portfolio"

class AboutMe extends JR.VIJAXX.Bio {
  const getDailyKnowledge = () => {
    return (
		[
		    id: 1, name: 'SCSS',
		    id: 2, name: 'JavaScript',
		    id: 3, name: 'React',
		    id: 4, name: 'GSAP'
		 ]
	   )
     }

    render (
      return (
	 <div>
	    {getDailyKnowledge().map(item => {
		return(
		  {item.id} {item.name}
		)
	    })}
	 </div>
	)
    )
}

export default AboutMe

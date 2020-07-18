[![](https://img.shields.io/badge/LinkedIn-JohnnyLU-blue)](https://www.linkedin.com/in/jl1829/)
[![](https://img.shields.io/badge/email-joh@johdev.com-red)](mailto:joh@johdev.com)
[![](https://img.shields.io/badge/HackerRank-johnnylou89-brightgreen)](https://www.hackerrank.com/johnnylou89)

```python
class README(object):
    """Doc String PlaceHolder"""

    def __init__(self, username='JL1829', year=2020):
        self.username = username
        self.FullName = 'Johnny(ZHIPING) Lu'
        self.education = {
            'Machine Learning': ['Machine Learning', 'Stanford Online',
                                 'Deep Learning', 'Coursera',
                                 'Mathematic for Machine Learning', 'Imperial College London'],
            'Master': ['MSc of Technology and Intelligent System', 'NUS'], 
        }
    
    def doing(self, now=2020):
        today = self.year
        
        if now == today:
            experience = self.employment['Lead Consulting Engineer']
            return """
            I am a Lead Consulting Engineer for Machine Learning and Data Science, current
            working project:
             - Customer purchase value prediction
             - Customer sentimental anaylser for review
             - Using Autoencoder for Computer Network Anomaly Detection.
            """
            learning = self.education.get('Master')
            
        if abs(now - today) > 4:
            experience = self.employment['System Engineer']
            return """
            I am a system engineer with around 10 years of solution design and 
            customer facing experiences, designing solution based on current
            product, as well as developing customized product for particular requirement."""
            
        if now > today:
            goal = self.employment['Machine Learning Engineer', 'Data Scientist']
            return """
            I am eager to explore the bigger world of Machine Learning and Data Science.
            **Open for Opportunity**
            """
            
        else:
            return """
            ### Hi there ~~
            """

me = README(2020)

```

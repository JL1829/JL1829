```python
class README(object):
    """Doc String PlaceHolder"""

    def __init__(self, username='JL1829', year=2020):
        self.username = username
        self.FullName = 'Johnny(ZHIPING) Lu'
        self.education = {
            'Machine Learning': ['Machine Learning', 'Stanford Online',
                                 'Deep Learning', 'Coursera'],
            'Master': ['MSc of Technology and Intelligent System', 'NUS'], 
        }
    
    def doing(self, year=2020):
        today = self.year

        if abs(now - today) > 4:
            experience = self.employment['System Engineer']
            return """
            I am a system engineer with around 10 years of solution design and 
            customer facing experiences, designing solution based on current
            product, as well as developing customized product for particular requirement."""

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
            

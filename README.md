class Gaby:

    def __init__(self):
        self.username = 'gabymy'
        self.name = 'Gabriela Mutilva'
        self.code = {
            'frontend': ['HTML', 'CSS', 'JavaScript', 'Angular', 'Boostrap'],
            'backend': ['Python', 'Flask', 'Django', 'Java'],
            'database': ['MySQL', 'Mongo DB'],
            'devops': ['Heroku'],
            'tools': ['GIT', 'GitHub', 'Pandas', 'Jupyter notebook'],
        }

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = gabymy()


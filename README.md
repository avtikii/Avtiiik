[![Braydon's GitHub Banner](./kut.jpeg)](https://en.wikipedia.org/wiki/Kutaisi)

import SoftwareDeveloper from 'Avtik';
import { Languages, Frameworks } from 'Avtiiik/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Avtandil Karkashadze';
  title    = 'Software Developer';
  location = 'Kutaisi, GE ';
}

class Skills extends SoftwareDeveloper {
  languages  = ['PHP', 'JavaScript', 'TypeScript', ...Languages];
  databases  = ['MySQL', 'PostgreSQL'];
  frameworks = ['Laravel', 'Vue', 'React', 'Next.js', 'Nest.js', ...Frameworks];

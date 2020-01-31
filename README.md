# cakephp-4-snippets README

### Cake PHP 4 snippets

## View

| Snippet   | Prefix  | Output                                                                                |
|-----------|---------|---------------------------------------------------------------------------------------|
| `success` | success | $this->Flash->success('Message');                                                     |
| `error`   | error   | $this->Flash->error('Message');                                                       |
| `create`  | create  | $this->Form->create('Model');                                                         |
| `end`     | end     | $this->Form->end();                                                                   |
| `control` | control | $this->Form->control('field');                                                        |
| `button`  | button  | $this->Form->button('title');                                                         |


## View(HTML)

| Snippet   | Prefix  | Output                                                                                |
|-----------|---------|---------------------------------------------------------------------------------------|
| `success` | success | \<\?= $this->Flash->success('Message') ?>                                             |
| `error`   | error   | \<\?= $this->Flash->error('Message') ?>                                               |
| `create`  | create  | \<\?= $this->Form->create('Model') ?>                                                 |
| `end`     | end     | \<\?= $this->Form->end() ?>                                                           |
| `control` | control | \<\?= $this->Form->control('field') ?>                                                |
| `button`  | button  | \<\?= $this->button('title') ?>                                                       |
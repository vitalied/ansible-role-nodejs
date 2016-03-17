Ansible Role for Node.js
====================

[![Build Status](https://travis-ci.org/vitalied/ansible-role-nodejs.svg?branch=master)](https://travis-ci.org/vitalied/ansible-role-nodejs)
[![GitHub tag](https://img.shields.io/github/tag/vitalied/ansible-role-nodejs.svg)](https://github.com/vitalied/ansible-role-nodejs)
[![GitHub license](https://img.shields.io/github/license/vitalied/ansible-role-nodejs.svg)](https://github.com/vitalied/ansible-role-nodejs/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/ansible/role/8589.svg)](https://galaxy.ansible.com/vitalied/nodejs)

Ansible Role for Node.js Management.

Requirements
------------

This role require Ansible 2.1 or higher.

This role was designed for Ubuntu Server 14.04+.

Role Variables
--------------

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>parameter</th>
<th>required</th>
<th>default</th>
<th>choices</th>
<th>comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>nodejs_version</td>
<td>yes</td>
<td>6.x</td>
<td><ul>
<li><code>6.x</code></li>
<li><code>5.x</code></li>
<li><code>4.x</code></li>
<li><code>0.10</code></li>
<li><code>etc...</code></li>
</ul></td>
<td>Version of Node.js to install.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: vitalied.nodejs

License
-------

-   Code released under [MIT](https://github.com/vitalied/ansible-role-nodejs/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

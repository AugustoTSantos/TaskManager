# TaskManager

## Project
A simple to-do list with spring-boot maven and h2 DB.

## Requirements
- Java 11 or superior
- Spring Boot
- H2 DB
- JPA/Hibernate
- Maven
- Spring Security
- Spring Data JPA
- JUnit e Mockito para testes


## User Stories
<table align="justify">
  <thead>
    <tr>
      <th>Name</th>
      <th>Story</th>
      <th>Short</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">User Registration</td>
      <td align="center">As the client, I need to create, read, update and delete users, so I have better control of my workforce.</td>
      <td align="center">UR</td>
    </tr>
    <tr>
      <td align="center">Task Management</td>
      <td align="center">As the client, I need to create, read, update and delete tasks and identify them with due dates, so I can document and plan what needs to be done, leading to better decisions.</td>
      <td align="center">TM</td>
    </tr>
    <tr>
      <td align="center">Filters and Sorting</td>
      <td align="center">As the client, I need to sort tasks by status and due date, so I can easily see how tasks are going and plan according to the deadline.</td>
      <td align="center">FS</td>
    </tr>
    <tr>
      <td align="center">Associating Tasks with Users</td>
      <td align="center">As the client, I need to associate tasks to users and filter tasks by associated users, so I can allocate resources effectively.</td>
      <td align="center">ATU</td>
    </tr>
  </tbody>
</table>

## Backlog
<table align="justify">
  <thead>
    <tr>
      <th>User Stories</th>
      <th>Epic</th>
      <th>About</th>
      <th>Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">ALL</td>
      <td align="center">base</td>
      <td align="center">This is the base that needs to be done, and well done, to start development.
</td>
      <td align="center">3</td>
    </tr>
    <tr>
      <td align="center">TM, FS, ATU</td>
      <td align="center">function</td>
      <td align="center">The “bread and butter” of the project.</td>
      <td align="center">2</td>
    </tr>
    <tr>
      <td align="center">TM, FS, ATU</td>
      <td align="center">tests</td>
      <td align="center">Garants if any of the functions needs to be updated or not.</td>
      <td align="center">2</td>
    </tr>
    <tr>
      <td align="center">UR</td>
      <td align="center">security</td>
      <td align="center">Give access to roles and protect accounts.</td>
      <td align="center">1</td>
    </tr>
  </tbody>
</table>

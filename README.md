# episode-2

# Q1)- What is NPM?
NPM is not abbreviated as Node Packet Manager although it manages all the node packets that we install in our system. In other words, npm is a large repository/library where all the files are available. It is initialised using "npm init" in the terminal. After pressing enter it will ask various details such as name, description, keywords, test..

# Q2)- What is Parcel/Webpack? Why do we need it?
Parcel/Webpack are the example of a Bundler. Bundler is a development tool that combines many JavaScript files into a single one, which is production ready loadable in the browser. It is used because in order to improve the speed of our app/website, it is vital. For example, when a project becomes too large for a single file or when working with libraries that have multiple dependencies, it is essential to bundle them together.
To include bundler we use "npm install -D parcel". -D because there are two types of dependencies. (A). Dev dependencies- there are required during the development phase , and (B)- Normal dependencies- they may be required in production or testing environment. Therefore, for Dev dependencies, we use "-D ".
# and All the bundling is done in development phase, thats why we install it in dev environment.

# Q3)- What is .parcel-cache?

# Q4)- What is npx?

# Q5)- What is the difference between dependencies and devDependencies?
(A). Dev dependencies- there are required during the development phase , and (B)- Normal dependencies- they may be required in production or testing environment.

# Q6)- What is Tree Shaking?

# Q7)- What is Hot Module Replacement?


# Q8)- List down your 5 favourite superpowers of Parcel and describe any 3 of them in your own words?



# Q9)- What is .gitignore? What should we add and not add into it?
.gitignore is a file in which we add/include all those files which we do not want to push to production in order to avoid bloating the space environment. The files which can be re-generated again should not be pushed to the production. Therefore, these files are added to .gitignore. Some examples are /node_modules , /dist and .parcel-cache.


# Q10)- What is the difference between the .package-json and .package-lock.json?
package.json holds important information about the project. Containing human-readable metadata about the project (like name, description) and functional metadata like package version and list of dependencies(either normal or dev) required by the application.
{It is needed because its a central place to configure and describe how to interact with and run your application. It identifies project's dependencies and how to handle them.}

package-lock.json holds the exact version unlike the package.json which can contain approx values(~,^). It ensures that the same dependencies are installed consistently across different environments, such as development and production. It also helps to prevent issues with installing different package versions which can lead to errors and conflicts.


# Q11)- Why should I not modify package-lock.json?
Because it is a generated file and should not be manually modified. It's purpose is to keep track of all the dependencies( and dependencies of dependencies) and their version, which changes with time. If we'll manually update it, it will break the synchronization between package.json and package-lock.json files.

# Q12)- What is node_modules? Is it a good idea to push it on Git?
node_modules is kind of a database which contains all the code that we fetched from npm. It includes multifarious files although we only needed parcel. It is done because parcel can have its own dependencies and those dependencies can again have their own dependencies and so on..( This is also referred as Transitive Dependencies.)


# Q13)- What is " dist " folder?



# Q14)- What is 'browserlists'. Read about different bundlers vite,webpack, parcel.



# Q15)- Explain Caret(^) and Tilda (~) in version?
At the outset, version is represented in this format. Major.Minor.Patch versions
Including Caret(^) will automatically update the future Minor and Patch versions into our file. For example, ^1.2.3 will go untill <1.3.0
Including Tilda(~) will automatically update to all future Patch versions only. For example, ~1.2.3 will go untill < 1.3.0
It is therefore advisable to use caret because it will keep the file updated, however, major updates should not be done as it could break our code.


# Q16)- Script types in HTML?



 

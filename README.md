###Frontend Responsive Boildeplate Code

A simple template with HTML, SASS and JS configured. To compile sass you can compile with vs code extension.

How to configure

1. Clone the repo git clone https://github.com/Chandrakanthpadi/responsive-boilerplate.git <YOUR_PROJECTNAME>
2. cd <YOUR_PROJECTNAME>
3. git remote remove origin
4. git remote add origin yourRemoteUrl

Follow the below order while writing the media queries

css_selector{
        //Styles for mobile
    @include breakpoint-up(medium){
        // Styles for tablets
    }
    @include breakpoint-up(large){
        // Styles for laptops
    }
}

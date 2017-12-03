```js
const resources = {
	bg: '/img/background.jpg',
	pattern: '/img/glow.png',
}
render(
    <Arwes resources={resources}>
        <div style={{ padding: 20 }}>
            <Project
                animate
                header='PROJECT, OFFICIA DESERUNT ANIM ID EST LABORUM'
                body={anim => (
                    <p><Words animate show={anim.entered}>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                        sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis laboris nisi ut aliquip
                        ex. Duis aute irure. Consectetur adipisicing elit, sed do
                        eiusmod tempor incididunt ut labore et dolore magna aliqua.
                        Ut enim ad minim veniam, quis nostrud.
                    </Words></p>
                )}
                footer={anim => (
                    <p><Words animate show={anim.entered}>Footer details</Words></p>
                )}
            />
        </div>
    </Arwes>
);
```
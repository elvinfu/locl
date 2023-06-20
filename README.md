# Locl

Locl is a platform that connects SNAP benefit users with local markets and farmers, allowing them to purchase healthy food options using their EBT cards. It addresses the limitations of the EBT system, which restricts food stamp acceptance to large chain grocery stores, often lacking diverse healthy options.

![Locl Logo](~/Locl Image.jpeg)

## Inspiration

Locl was inspired by the need to provide access to fresh, healthy food for under-resourced communities, especially during times of crisis such as the COVID-19 pandemic. The sudden closure of schools disrupted government-provided food programs, placing the burden of purchasing nutritious food on parents. Many families heavily relied on SNAP benefits to meet their basic needs. However, the limited acceptance of EBT payments at large chain grocery stores prevented access to locally sourced, sustainable produce.

## How Locl Works

Locl acts as a virtual farmers market, bringing together multiple local producers on one platform. SNAP benefit users can convert their EBT balance into Locl credits and spend them on carefully curated produce from local suppliers. This promotes better eating habits, supports local markets and farmers, and increases the accessibility of fresh, healthy food for low-income individuals and families.

## Key Features

- EBT Support: Locl allows users to convert their EBT balance into Locl credits and spend them on ethically sourced produce, adhering to SNAP regulations.
- Bank-less Payment: To facilitate transactions between shoppers and vendors, Locl integrates Checkbook.io's virtual credit cards and direct deposit services, removing the need for a bank account.
- Producer Accessibility: By consolidating multiple vendors on one platform, Locl increases the accessibility of smaller producers and promotes a diverse range of healthy food options.
- Recognizable Marketplace: Locl's user interface is designed to resemble popular marketplace applications, making it easy for users to navigate and engage with the platform.

## Technologies Used

- Flask: The Locl server is built using Flask, a Python web framework, to handle requests and populate the website with data.
- Supabase and PostgreSQL: Locl utilizes Supabase, a PostgreSQL-based backend, to store product, market, virtual credit card, and user information.
- Checkbook.io: Checkbook.io's Payfac API enables secure transactions between shoppers and vendors, providing a bank-less solution for low-income shoppers.

## Challenges and Future Development

During the development process, the team encountered challenges in integrating various APIs and creating a refined user experience. In the future, Locl aims to enhance the platform with features such as a search and filtering system, an automated redemption process with the state government for EBT, and improved security and encryption for all API calls and database queries.

## Ethics and Considerations

Locl strives to address the ethical concerns of limited access to healthy foods for SNAP benefit users. However, it acknowledges the challenges of technological barriers and potential imbalances in product representation. Efforts are being made to refine the algorithm and ensure equity among all stakeholders. Locl also aims to increase awareness and accessibility, particularly among SNAP beneficiaries who may not be aware of online purchasing options.

## Conclusion

Locl is dedicated to bridging the gap between EBT cardholders and fresh, locally sourced produce. By providing a platform that supports EBT payments and connects users with local markets and farmers, Locl aims to improve food access, nutrition, and overall well-being for under-resourced communities.

## Start

First activate virtual python environment

```cd locl && virtualenv .env && source .env/bin/activate && pip3 install supabase && pip3 install flask```

Next, start Flask server

```cd flaskr && flask run```

Open server on localhost 127.0.0.1

## Usage

From here, you can create an account and access the marketplace. Click redeem to transfer funds from EBT to Locl. Browse the product selection on marketplace and buy what you're interested in with just a click.

# Environment Variables
Supabase password: loclisreallycool

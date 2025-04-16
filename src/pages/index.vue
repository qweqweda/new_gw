<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
const APPNAME = 'Jerik'
const EMAILADDRESS = '@'
</script>

<template>
  <div class="bg">
    <div class="agreement">
      <div class="T_title_main">
        Terms of Use
      </div>
      <div class="T_content">
        Welcome to {{ APPNAME }}.
        By accessing or using the {{ APPNAME }} mobile application, whether through a mobile device or computer (collectively, the “Service”), you agree to be bound by these Terms of Use (this “Agreement”), whether or not you create a {{ APPNAME }} account. If you wish to create a {{ APPNAME }} account and use the Services, Please review the terms described herein carefully.
      </div>

      <!--  -->
      <div class="T_title">
        CONTACTING US
      </div>
      <div class="T_content">
        If you have any questions about this Terms of Use, please contact us: {{ EMAILADDRESS }}.
      </div>

      <!-- 1 -->
      <div class="T_title">
        1. ACCOUNT ELIGIBILITY; YOUR RESPONSIBILITIES
      </div>
      <div class="T_title_secondary">
        Before you create an account on {{ APPNAME }}, make sure you are eligible to use our Services. This Section also details what you can and can't do when using the Services, as well as the rights you grant {{ APPNAME }}.
        <br><br>
        You are not authorized to create an account or use the Services unless all of the following are true, and by using our Services, you represent and warrant that:
      </div>
      <div class="T_content" style="padding-left: 35px;">
        <li>
          You are an individual (i.e., not any body corporate, partnership or other business entity) at least 17 years old;
        </li>
        <li>
          You are not on any list of individuals prohibited from conducting business with the United States (for example, the U.S. Treasury Department’s list of Specially Designated Nationals or any similar government agency list) nor do you face any other similar prohibition);
        </li>
        <li>
          You are not prohibited by law from using our Services;
        </li>
        <li>
          You have not committed, been convicted of, or pled no contest to a felony or indictable offense (or crime of similar severity), a sex crime, or any crime involving violence or a threat of violence, unless you have received clemency for a non-violent crime and we have determined that you are not likely to pose a threat to other users of our Services;
        </li>
        <li>
          You are legally qualified to enter a binding contract with {{ APPNAME }};
        </li>
        <li>
          You are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country;
        </li>
        <li>
          You are not required to register as a sex offender with any state, federal or local sex offender registry;
        </li>
        <li>
          You do not have more than one account on our Services;
        </li>
        <li>
          You have not previously been removed from our Services or our affiliates’ services by us or our affiliates, unless you have our express written permission to create a new account.
        </li>
      </div>
      <div class="T_title_secondary">
        If at any time you cease to meet these requirements, all authorization to access our Services or systems is automatically revoked, and you must immediately delete your account, and we retain the right to remove your access to our Services without warning.
        <br>
        You agree to:
      </div>
      <div class="T_content" style="padding-left: 35px;">
        <li>Comply with these Terms, and check this page from time to time to ensure you are aware of any changes;</li>
        <li>Comply with all applicable laws, including without limitation, privacy laws, intellectual property laws, anti-spam laws, and regulatory requirements;</li>
        <li>Use the latest version of the Website and/or App;</li>
        <li>Take reasonable measures to protect the security of your login information.</li>
      </div>
      <div class="T_title_secondary">
        You agree that you will not:
      </div>
      <div class="T_content" style="padding-left: 35px;">
        <li>Misrepresent your identity, age, or affiliations with a person or entity;</li>
        <li>Use the Services in a way that damages the Services or prevents their use by other users;</li>
        <li>Use our Services in a way to interfere with, disrupt or negatively affect the platform, the servers, or our Services' networks;</li>
        <li>Use our Services for any harmful, illegal, or nefarious purpose, including, but not limited to, using any In-App Items for purposes of money laundering or other financial crimes;</li>
        <li>Harass, bully, stalk, intimidate, assault, defame, harm or otherwise abuse or cause psychological harm to any other user of the Services;</li>
        <li>Post, display or share Prohibited Content (see below);</li>
        <li>Solicit passwords for any purpose, or personal identifying information for commercial or unlawful purposes from other users or disseminate another person's personal information without his or her permission;</li>
        <li>Solicit money or other items of value from another user, whether as a gift, loan, or form of compensation;</li>
        <li>Use our Services in relation to fraud, a pyramid scheme, or other similar practice;</li>
        <li>Use our Services in relation to any political campaign financing or for the purpose of influencing any election, other than sharing your own personal political opinions.</li>
        <li>Use meta tags or code or other devices containing any reference to a third party platform (or any trademark, trade name, service mark, logo or slogan of a third party), with the intention and/or objective to direct any user of the Service to any other website for any purpose;</li>
        <li>Modify, adapt, sublicense, translate, sell, reverse engineer, decipher, decompile or otherwise disassemble any portion of our Services, or cause others to do so;</li>
      </div>
      <div class="T_title_secondary">
        Prohibited Content - {{ APPNAME }} prohibits displaying or sharing content that:
      </div>
      <div class="T_content" style="padding-left: 35px;">
        <li>Could reasonably be deemed to be offensive or to harass, abuse or cause psychological distress to another person;</li>
        <li>Is obscene, pornographic, violent or contains nudity;</li>
        <li>Is abusive, threatening, discriminatory or that promotes or encourages racism, sexism, hatred or bigotry;</li>
        <li>Encourages or facilitates any illegal activity including, without limitation, terrorism, inciting racial hatred or the submission of which in itself constitutes committing a criminal offense;</li>
        <li>Encourages or facilitates any activity that may result in harm to the user or another person, including, but not limited to, promotion of self-harm, eating disorders, dangerous challenges, violent extremism,</li>
        <li>Is defamatory, libelous, or untrue;</li>
        <li>Relates to commercial activities (including, without limitation, sales, competitions, promotions, and advertising, solicitation for services, sex work, "sugar daddy" or "sugar baby" relationships, links to other websites or premium line telephone numbers);</li>
        <li>Involves or facilitates the transmission of spam;</li>
      </div>
      <!-- 2 -->
      <div class="T_title">
        2. CONTENT
      </div>
      <div class="T_title_secondary">
        It is important that you understand your rights and responsibilities with regard to the content on our Services, including any content you provide, share or post. You are expressly prohibited from posting inappropriate content.
      </div>
      <div class="T_content">
        While using our Services, you will have access to: (i) content that you upload, display, share or provide while using our Services, even if suggested by our Services ("Your Content"); (ii) content that other users upload, display, share or provide while using our Services ("Member Content"); and (iii) content that {{ APPNAME }} provides on and through our Services ("Our Content"). In this agreement, "content" includes, without limitation, all text, images, video, audio, or other material on our Services, including information on users' profiles and in direct messages between users.
        <br><br>
        You are solely responsible and liable for Your Content, and, therefore, you agree to indemnify, defend, release, and hold us harmless from any claims made in connection with Your Content.
        <br><br>
        You represent and warrant to us that the information you provide to us or any other user is accurate, including any information submitted through any other third-party sources (if applicable), and that you will update your account information as necessary to ensure its accuracy.
        <br><br>
        The content included on your individual profile should be relevant to the intended use of our Services. You may not share any Prohibited Content, and your content must further comply with the Community Guidelines. You may not display any personal contact, banking information, or peer-to-peer payment information, whether in relation to you or any other person (for example, names, home addresses or postcodes, telephone numbers, email addresses, URLs, credit/debit card, peer-to-peer payment user name, or other banking details). IF YOU CHOOSE TO REVEAL ANY PERSONAL INFORMATION ABOUT YOURSELF TO OTHER USERS, YOU DO SO AT YOUR OWN RISK. WE STRONGLY ENCOURAGE YOU TO USE CAUTION IN DISCLOSING ANY PERSONAL INFORMATION ONLINE.
        <br><br>
        Your individual profile will be visible to other people around the world, so be sure that you are comfortable sharing Your Content before you share. You acknowledge and agree that Your Content may be viewed by other users, and, notwithstanding these Terms, other users may share Your Content with third parties. By sharing and/or streaming Your Content, you represent and warrant to us that you have all necessary rights and licenses to do so and automatically grant us a license to use Your Content as provided under Section 7 below.
        <br><br>
        We may provide tools and features to enhance individual expression through Your Content and Member Content, and we’re constantly developing new technologies to improve our Services. Certain tools or features may allow you to generate or enhance content based on Your Content. This is still Your Content, and you are responsible for it and its accuracy, as well as your use of it on our Services and any and all decisions made, actions taken, and failures to take action based on Your Content. Be careful in choosing and sharing Your Content.
        <br><br>
        You understand and agree that we may monitor or review Your Content, and we have the right to remove, delete, edit, limit, or block or prevent access to any of Your Content at any time at our sole discretion. Furthermore, you understand and agree that we have no obligation to display or review Your Content.
        <br><br>
        Any other text, content, graphics, user interfaces, trademarks, logos, sounds, artwork, images, and other intellectual property appearing on our Services is owned, controlled or licensed by us and protected by copyright, trademark and other intellectual property law rights. All rights, title, and interest in and to Our Content remains with us at all times.
        <br><br>
        We grant you a limited license to access and use our content, and we reserve all other rights.
      </div>

      <!-- 3 -->
      <div class="T_title">
        3. INAPPROPRIATE CONTENT AND MISCONDUCT; REPORTING
      </div>
      <div class="T_title_secondary">
        {{ APPNAME }} does not tolerate inappropriate content or behavior on our Services.
      </div>
      <div class="T_content">
        We are committed to maintaining a positive, respectful community, and we do not tolerate any inappropriate content or inappropriate behavior, whether on or off the Service (including, but not limited to, services operated by our affiliates). We encourage you to report any inappropriate Member Content or inappropriate behavior by other users. You can report a user directly by clicking the shield icon in the user's profile or messaging experience. You can also contact customer support.
        <br><br>
        As described in our Privacy Policy, we may share data among our affiliates to ensure the safety of our users. If we believe that you have violated these terms, we may take necessary action, including prohibiting you from using our Services and/or the services of our affiliates, and/or preventing you from creating new accounts. You understand and agree that we may not share information about your account with you if doing so may compromise the safety or privacy of our other users.
      </div>

      <!-- 4 -->
      <div class="T_title">
        4. RIGHTS YOU ARE GRANTED BY {{ APPNAME }}
      </div>
      <div class="T_title_secondary">
        {{ APPNAME }} grants you the right to use and enjoy our Services, subject to these Terms.
      </div>
      <div class="T_content">
        For as long as you comply with these Terms, {{ APPNAME }} grants you a personal, worldwide, royalty-free, non-assignable, non-exclusive, revocable, and non-sublicensable license to access and use our Services for purposes as intended by {{ APPNAME }} and permitted by these Terms and applicable laws. This license and any authorization to access the Service are automatically revoked in the event that you fail to comply with these Terms.
      </div>

      <!-- 5 -->
      <div class="T_title">
        5. RIGHTS YOU GRANT {{ APPNAME }}
      </div>
      <div class="T_title_secondary">
        You own all of the content you provide to {{ APPNAME }}, but you also grant us the right to use Your Content as provided in this Agreement.
      </div>
      <div class="T_content">
        By creating an account, you grant to {{ APPNAME }} a worldwide, perpetual, transferable, sub-licensable, royalty-free right and license to host, store, use, copy, display, reproduce, adapt, edit, publish, translate, modify, reformat, incorporate into other works, advertise, distribute and otherwise make available to the general public Your Content, including any information you authorize us to access from any other third-party sources (if applicable), in whole or in part, and in any way and in any format or medium currently known or developed in the future. {{ APPNAME }}'s license to Your Content shall be non-exclusive, except that {{ APPNAME }}'s license shall be exclusive with respect to derivative works created through use of our Services. For example, {{ APPNAME }} would have an exclusive license to screenshots of our Services that include Your Content.
        <br><br>
        In addition, so that {{ APPNAME }} can prevent the use of Your Content outside of our Services, you authorize {{ APPNAME }} to act on your behalf with respect to infringing uses of Your Content taken from our Services by other users or third parties. This expressly includes the authority, but not the obligation, to send notices pursuant to 17 U.S.C. § 512(c)(3) (i.e., DMCA Takedown Notices) on your behalf if Your Content is taken and used by third parties outside of our Services. {{ APPNAME }} is not obligated to take any action with regard to use of Your Content by other users or third parties. {{ APPNAME }}'s license to Your Content is subject to your rights under applicable law (for example, laws regarding personal data protection to the extent the content contains personal information as defined by those laws).
        <br><br>
        In consideration for {{ APPNAME }} allowing you to use our Services, you agree that we, our affiliates, and our third-party partners may place advertising on our Services. By submitting suggestions or feedback to {{ APPNAME }} regarding our Services, you agree that {{ APPNAME }} may use and share such feedback for any purpose without compensating you.
        <br><br>
        You agree that {{ APPNAME }} may access, preserve, and disclose your account information, including Your Content, if required to do so by law or upon a good faith belief that such access, preservation, or disclosure is reasonably necessary to: (i) comply with legal process; (ii) enforce these Terms; (iii) respond to claims that any content violates the rights of third parties; (iv) respond to your requests for customer service; (v) protect the rights, property or personal safety of the Company or any other person, or (vi) to investigate, prevent, or take other action regarding illegal activity, suspected fraud or other wrongdoing.
        <br><br>
      </div>

      <!-- 6 -->
      <div class="T_title">
        6. IN APP PURCHASES
      </div>
      <div class="T_content">
        From time to time, {{ APPNAME }} may offer additional products and services for purchase through the App Store ℠, Google Play or other application platforms ("in app purchases"). If you choose to make an in app purchase, you will be prompted to enter details for your account with the mobile platform you are using (e.g., Apple, Android, etc.) ("your IAP Account"), and your IAP Account will be charged for the in app purchase in accordance with the terms disclosed to you at the time of purchase as well as the general terms for in app purchases that apply to your IAP Account. If you purchase an auto-recurring periodic subscription through an in app purchase, your IAP Account will be billed continuously for the subscription until you cancel in accordance with the platform terms. In call cases, please refer to the terms of your application platform which apply to your in app purchases. {{ APPNAME }} do not have any obligation to terminate your subscription or membership, but you can claim a refund or cancel the subscription through App Store or Google Play at any time.
      </div>

      <!-- 7 -->
      <div class="T_title">
        7. ACCOUNT TERMINATION
      </div>
      <div class="T_title_secondary">
        If you no longer wish to use our Services, or if we terminate your account for any reason, here's what you need to know.
      </div>
      <div class="T_content">
        You can delete your account at any time by logging into the Website or App, going to “Account settings” on my profile Settings, clicking "Delete Account", and following the instructions to complete the deletion process. However, you will need to cancel / manage any External Service Purchases through your External Service Account (e.g., iTunes, Google Play) to avoid additional billing.
        <br><br>
        {{ APPNAME }} reserves the right to investigate and, if appropriate, suspend or terminate your account without a refund if {{ APPNAME }} believes that you have violated these Terms, misused our Services, or behaved in a way that {{ APPNAME }} regards as inappropriate or unlawful, on or off our Services. We reserve the right to make use of any personal, technological, legal, or other means available to enforce the Terms, at any time without liability and without the obligation to give you prior notice, including, but not limited to, preventing you from accessing the Services.
        <br><br>
        If your account is terminated by you or by {{ APPNAME }} for any reason, these Terms continue and remain enforceable between you and {{ APPNAME }}, and you will not be entitled to any refund for purchases made. Your information will be maintained and deleted in accordance with our Privacy Policy.
      </div>

      <!-- 8 -->
      <div class="T_title">
        8. NO CRIMINAL BACKGROUND OR IDENTITY VERIFICATION CHECKS
      </div>
      <div class="T_title_secondary">
        {{ APPNAME }} does not conduct criminal background or identity verification checks on its users. Though {{ APPNAME }} strives to encourage a respectful user experience, it is not responsible for the conduct of any user on or off the Service. Use your best judgment when interacting with others and review our Safety Tips.
      </div>
      <div class="T_content">
        You understand that {{ APPNAME }} does not conduct criminal background or identity verification checks on its users or otherwise investigate the backgrounds of its users. {{ APPNAME }} makes no representations or warranties regarding the conduct, identity, health, physical condition, intentions, legality, or authenticity of its users. {{ APPNAME }} reserves the right (and you authorize {{ APPNAME }} to do so) to conduct any criminal background check or other screening (e.g., sex offender registry search) at any time using available public records, and you agree that any information you provide may be used for such purpose. If the Company decides to conduct any screening through a consumer reporting agency, you hereby authorize the Company to obtain and use a consumer report about you to determine whether you qualify for these Terms.
        <br><br>
        You are solely responsible for your interactions with other users. We cannot and do not guarantee your safety and are not a substitute for following safety tips and other reasonable safety precautions. Always use your best judgment and take appropriate safety precautions when communicating with or meeting new people. Communications received through the Service, including automated notifications sent by {{ APPNAME }}, may be the result of users using the Service for improper purposes, including fraud, abuse, harassment, or other such inappropriate behavior.
        <br><br>
        While {{ APPNAME }} strives to encourage a respectful user experience, it is not responsible for the conduct of any user on or off the Service. You agree to exercise caution in all interactions with other users, especially when you decide to communicate outside the Service or meet in person.
      </div>

      <!-- 9 -->
      <div class="T_title">
        9. DISCLAIMER
      </div>
      <div class="T_title_secondary">
        {{ APPNAME }}'s Services are provided "as is" and we do not make, and cannot make, any representations about the content or features of our Services or Member Content.
      </div>
      <div class="T_content">
        {{ APPNAME }} provides our services on an “as is” and “as available” basis and, to the extent permitted by applicable law, disclaims all warranties of any kind, whether express, implied, statutory or otherwise, with respect to our services (including all content contained therein). (including all content contained therein), including, but not limited to, any implied warranties of satisfactory quality, merchantability, fitness for a particular purpose or non-infringement. {{ APPNAME }} does not represent or warrant that: (a) our services will be uninterrupted, secure or error-free; (b) any defects or errors in our services will be discovered or corrected; or (c) any content or information you obtain on or through our services will be accurate, complete, current or fit for your purposes. In addition, {{ APPNAME }} does not guarantee the number of active Users at any given time; the ability or desire of Users to communicate with or meet you, or the ultimate compatibility or behavior of Users you meet through the Services.
        <br><br>
        {{ APPNAME }} is not responsible for any content posted, sent, received or performed by you or other Users or third parties through our Services, nor is {{ APPNAME }} responsible for the identity, intent, legality or authenticity of any Users with whom you may communicate through {{ APPNAME }}. Any material downloaded or otherwise obtained through the use of our Services is done at your own discretion and risk. {{ APPNAME }} shall not be liable for any damages to your computer hardware, computer software or other equipment or technology, including, but not limited to, damages resulting from any security breach, any virus, bug, bug, tampering, hacking, fraud, error, omission, interruption, defect, delay in operation or transmission, computer line or network failure, or any other technical or other interruption or failure.
      </div>

      <!-- 10 -->
      <div class="T_title">
        10. ADS AND THIRD-PARTY CONTENT
      </div>
      <div class="T_title_secondary">
        You may see ads and third-party promotions on our Services. {{ APPNAME }} does not endorse and isn’t responsible for your interactions with those products or services.
      </div>
      <div class="T_content">
        Our Services may contain advertisements and promotions offered by third parties and links to other websites or resources. In addition, our Services may allow you to watch an advertisement in exchange for In-App Items; {{ APPNAME }} does not guarantee that you will always be eligible to watch such advertisements, or that any such advertisements will be available. {{ APPNAME }} may also provide non-commercial links or references to third parties within its content. {{ APPNAME }} is not responsible for the availability (or lack of availability) of any external websites or resources or their content. Furthermore, {{ APPNAME }} is not responsible for, and does not endorse, any products or services that may be offered by third-party websites or resources. If you choose to interact with the third parties made available through our Services, such party's terms will govern their relationship with you. {{ APPNAME }} is not responsible or liable for such third parties' terms or actions.
      </div>

      <!-- 11 -->
      <div class="T_title">
        11. LIABILITY
      </div>
      <div class="T_title_secondary">
        {{ APPNAME }}'s liability is limited to the maximum extent allowed by applicable law.
      </div>
      <div class="T_content">
        to the maximum extent permitted by applicable law, in no event shall {{ APPNAME }}, its affiliates, employees, licensors or service providers be liable for any indirect, consequential, exemplary, incidental, special, punitive, fixed or enhanced damages, including, but not limited to, loss of profits (whether directly or indirectly caused), or any loss of data, loss of use, loss of goodwill, or other intangible loss These damages arise from: (I) your access to, use of, or inability to access or use the Services, (II) the conduct or content of any user or third party on or through any of the Services, the services of our affiliates, or in connection with the Services; or (III) any unauthorized access to, use of, or alteration of your content, even if {{ APPNAME }} has been advised of the possibility of such damages. to the maximum extent permitted by applicable law, in no event shall {{ APPNAME }}'s total liability to you for all claims relating to the services exceed the greater of (a) one hundred dollars ($100) or (b) the amount, if any, paid by you to {{ APPNAME }} for the services during the twenty-four (24) month period prior to the date on which an action, arbitration, or any other proceeding is first instituted against {{ APPNAME }} in any court, whether statutory, legal, or equitable. statutory, legal or equitable. The limitation on damages set forth in the preceding sentence applies (i) regardless of the basis of liability (whether for breach of contract, contract, tort, statute or otherwise), (ii) regardless of the type of breach of right, privilege or obligation, and (iii) to all Events, Services and this Agreement.
        <br><br>
        the limitation of liability provisions set forth in this section apply even if your remedies under this agreement fail of their essential purpose.
        <br><br>
        some jurisdictions do not allow limitations on certain damages, so some or all of the limitations in this section may not apply to you.
      </div>

      <!-- 12 -->
      <div class="T_title">
        12. ACCEPTANCE OF TERMS
      </div>
      <div class="T_title_secondary">
        By using our Services, you accept the Terms of this Agreement.
      </div>
      <div class="T_content">
        By using our Services, whether through a mobile device, mobile application or computer, you agree to be bound by: (i) these Terms as we may modify from time to time; (ii) our Privacy Policy, User Policy; and (iii) any additional terms at the time of purchase. If you do not accept and agree to be bound by all the terms of this Agreement, you are not authorized to use our Services.
        <br><br>
        All pronouns and any variations thereof shall be deemed to refer to the masculine, feminine, neuter, singular or plural of any entity or person to be referred to.
        <br><br>
      </div>
    </div>
  </div>
</template>

<style  scoped>
  .agreement {
  padding: 10px 20px;
  font-size: 14px;
  margin-bottom: 14px;
  color: #000;
  background-color: #fff;
}
.T_title_main {
  font-size: 30px;
  font-weight: 900;
  margin: 1rem 0px;
  color: #000;
}
.T_title {
  font-size: 18px;
  font-weight: 700;
  margin: 1rem 0px;
  color: #000;
}
.T_title_secondary {
  font-size: 16px;
  font-weight: 500;
  margin: 1rem 0px;
  color: #000;
}
.T_content {
  font-size: 14px;
  font-weight: 400;
  margin-bottom: 12px;
  color: #0e0d0d;
}
.bg {
  padding: 50px 50px;
  background-color: #f5f6f7;
}
</style>

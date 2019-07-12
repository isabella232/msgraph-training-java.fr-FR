---
ms.openlocfilehash: 97763f135ab7529cfbcebf2eaf4d4d98d234fe10
ms.sourcegitcommit: 02054b307013cce781be2a3512ec1e54f1a322eb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/12/2019
ms.locfileid: "35634730"
---
<!-- markdownlint-disable MD002 MD041 -->

<span data-ttu-id="ac8ff-101">Dans cet exercice, vous allez créer une nouvelle application Azure AD à l’aide du centre d’administration Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-101">In this exercise you will create a new Azure AD application using the Azure Active Directory admin center.</span></span>

1. <span data-ttu-id="ac8ff-102">Ouvrez un navigateur, accédez au [Centre d’administration Azure Active Directory ](https://aad.portal.azure.com) et connectez-vous à l’aide d’un **compte personnel** (ou compte Microsoft) ou d’un **compte professionnel ou scolaire**.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-102">Open a browser and navigate to the [Azure Active Directory admin center](https://aad.portal.azure.com) and login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="ac8ff-103">Sélectionnez **Azure Active Directory** dans le volet de navigation de gauche, puis sélectionnez **inscriptions des applications** sous **gérer**.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-103">Select **Azure Active Directory** in the left-hand navigation, then select **App registrations** under **Manage**.</span></span>

    ![<span data-ttu-id="ac8ff-104">Capture d’écran des inscriptions d’application</span><span class="sxs-lookup"><span data-stu-id="ac8ff-104">A screenshot of the App registrations</span></span> ](./images/aad-portal-app-registrations.png)

1. <span data-ttu-id="ac8ff-105">Sélectionnez **Nouvelle inscription**.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-105">Select **New registration**.</span></span> <span data-ttu-id="ac8ff-106">Sur la page **Inscrire une application**, définissez les valeurs comme suit.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-106">On the **Register an application** page, set the values as follows.</span></span>

    - <span data-ttu-id="ac8ff-107">Définissez le **Nom** sur `Java Graph Tutorial`.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-107">Set **Name** to `Java Graph Tutorial`.</span></span>
    - <span data-ttu-id="ac8ff-108">Définissez les types de comptes **pris en charge** sur **les comptes dans n’importe quel annuaire d’organisation**.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-108">Set **Supported account types** to **Accounts in any organizational directory**.</span></span>
    - <span data-ttu-id="ac8ff-109">Laissez **Redirect URI** vide.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-109">Leave **Redirect URI** empty.</span></span>

    ![Capture d’écran de la page inscrire une application](./images/aad-register-an-app.png)

1. <span data-ttu-id="ac8ff-111">Choisissez **Inscrire**.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-111">Choose **Register**.</span></span> <span data-ttu-id="ac8ff-112">Sur la page **didacticiel de Graph Java** , copiez la valeur de l' **ID d’application (client)** et enregistrez-la, vous en aurez besoin à l’étape suivante.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-112">On the **Java Graph Tutorial** page, copy the value of the **Application (client) ID** and save it, you will need it in the next step.</span></span>

    ![Capture d’écran de l’ID d’application de la nouvelle inscription de l’application](./images/aad-application-id.png)

1. <span data-ttu-id="ac8ff-114">Sélectionnez le lien **Ajouter un URI de redirection** .</span><span class="sxs-lookup"><span data-stu-id="ac8ff-114">Select the **Add a Redirect URI** link.</span></span> <span data-ttu-id="ac8ff-115">Sur la page **URI** de redirection, recherchez la section **URI de redirection suggérée pour les clients publics (mobile, bureau)** .</span><span class="sxs-lookup"><span data-stu-id="ac8ff-115">On the **Redirect URIs** page, locate the **Suggested Redirect URIs for public clients (mobile, desktop)** section.</span></span> <span data-ttu-id="ac8ff-116">Sélectionnez l' `https://login.microsoftonline.com/common/oauth2/nativeclient` URI.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-116">Select the `https://login.microsoftonline.com/common/oauth2/nativeclient` URI.</span></span>

    ![Capture d’écran de la page des URI de redirection](./images/aad-redirect-uris.png)

1. <span data-ttu-id="ac8ff-118">Recherchez la section **type de client par défaut** et modifiez le paramètre **traiter l’application comme un client public** sur **Oui**, puis cliquez sur **Enregistrer**.</span><span class="sxs-lookup"><span data-stu-id="ac8ff-118">Locate the **Default client type** section and change the **Treat application as a public client** toggle to **Yes**, then choose **Save**.</span></span>

    ![Capture d’écran de la section type de client par défaut](./images/aad-default-client-type.png)

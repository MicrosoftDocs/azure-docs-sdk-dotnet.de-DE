<Type Name="PromptBehavior" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior">
  <TypeSignature Language="C#" Value="public enum PromptBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PromptBehavior extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior" />
  <TypeSignature Language="VB.NET" Value="Public Enum PromptBehavior" />
  <TypeSignature Language="F#" Value="type PromptBehavior = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="9fe74-101">Gibt an, ob AcquireToken nur bei Bedarf automatisch auffordern soll, oder gibt an, ob die Warnung unabhängig davon, ob anzeigen soll ein zwischengespeichertes Token vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="9fe74-101">Indicates whether AcquireToken should automatically prompt only if necessary or whether it should prompt regardless of whether there is a cached token.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Always">
      <MemberSignature Language="C#" Value="Always" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior Always = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Always" />
      <MemberSignature Language="VB.NET" Value="Always" />
      <MemberSignature Language="F#" Value="Always = 1" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Always" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9fe74-102">Der Benutzer wird zum Eingeben von Anmeldeinformationen aufgefordert werden, auch wenn es ein Token, das die bereits im Cache erfüllt.</span><span class="sxs-lookup"><span data-stu-id="9fe74-102">The user will be prompted for credentials even if there is a token that meets the requirements already in the cache.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Auto">
      <MemberSignature Language="C#" Value="Auto" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior Auto = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Auto" />
      <MemberSignature Language="VB.NET" Value="Auto" />
      <MemberSignature Language="F#" Value="Auto = 0" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Auto" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9fe74-103">Erwerben Token wird der Benutzer zum Eingeben von Anmeldeinformationen nur bei Bedarf aufgefordert.</span><span class="sxs-lookup"><span data-stu-id="9fe74-103">Acquire token will prompt the user for credentials only when necessary.</span></span>  <span data-ttu-id="9fe74-104">Wenn ein Token, das die Anforderungen erfüllt bereits zwischengespeichert wird wird der Benutzer nicht aufgefordert werden.</span><span class="sxs-lookup"><span data-stu-id="9fe74-104">If a token that meets the requirements is already cached then the user will not be prompted.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Never">
      <MemberSignature Language="C#" Value="Never" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior Never = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Never" />
      <MemberSignature Language="VB.NET" Value="Never" />
      <MemberSignature Language="F#" Value="Never = 2" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Never" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9fe74-105">Der Benutzer wird nicht zum Eingeben von Anmeldeinformationen aufgefordert werden.</span><span class="sxs-lookup"><span data-stu-id="9fe74-105">The user will not be prompted for credentials.</span></span>  <span data-ttu-id="9fe74-106">Wenn eine Bestätigung erforderlich ist, wird die AcquireToken-Anforderung fehl.</span><span class="sxs-lookup"><span data-stu-id="9fe74-106">If prompting is necessary then the AcquireToken request will fail.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RefreshSession">
      <MemberSignature Language="C#" Value="RefreshSession" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior RefreshSession = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.RefreshSession" />
      <MemberSignature Language="VB.NET" Value="RefreshSession" />
      <MemberSignature Language="F#" Value="RefreshSession = 3" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.RefreshSession" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9fe74-107">(Über das Anzeigen von Webview) erneut autorisiert die Ressourcenverwendung, stellen Sie sicher, dass das resultierende Zugriffstoken aktualisierte Ansprüche enthält.</span><span class="sxs-lookup"><span data-stu-id="9fe74-107">Re-authorizes (through displaying webview) the resource usage, making sure that the resulting access token contains updated claims.</span></span> <span data-ttu-id="9fe74-108">Wenn Benutzer Anmeldung Cookies zur Verfügung stehen, die Benutzer werden nicht erneut zum Eingeben von Anmeldeinformationen aufgefordert und das Anmeldedialogfeld wird automatisch verworfen werden.</span><span class="sxs-lookup"><span data-stu-id="9fe74-108">If user logon cookies are available, the user will not be asked for credentials again and the logon dialog will dismiss automatically.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="SelectAccount">
      <MemberSignature Language="C#" Value="SelectAccount" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior SelectAccount = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.SelectAccount" />
      <MemberSignature Language="VB.NET" Value="SelectAccount" />
      <MemberSignature Language="F#" Value="SelectAccount = 4" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.SelectAccount" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9fe74-109">Der Benutzer aufgefordert, ein Benutzerkonto auswählen, auch wenn es ein Token, das die bereits im Cache erfüllt.</span><span class="sxs-lookup"><span data-stu-id="9fe74-109">Prompt the user to select a user account even if there is a token that meets the requirements already in the cache.</span></span> <span data-ttu-id="9fe74-110">Dadurch wird einen Benutzer verfügt über mehrere Konten auf dem Autorisierungsserver für mehrere Konten auswählen, die sie möglicherweise die aktuellen Sitzungen für verfügen.</span><span class="sxs-lookup"><span data-stu-id="9fe74-110">This enables an user who has multiple accounts at the Authorization Server to select amongst the multiple accounts that they might have current sessions for.</span></span> 
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="PrivateRegistryCredentials" FullName="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials">
  <TypeSignature Language="C#" Value="public class PrivateRegistryCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PrivateRegistryCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class PrivateRegistryCredentials" />
  <TypeSignature Language="F#" Value="type PrivateRegistryCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="caea8-101">Anmeldeinformationen für den Zugriff auf ein containerimage in einem privaten Repository.</span><span class="sxs-lookup"><span data-stu-id="caea8-101">Credentials to access a container image in a private repository.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PrivateRegistryCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="caea8-102">Initialisiert eine neue Instanz der PrivateRegistryCredentials-Klasse.</span><span class="sxs-lookup"><span data-stu-id="caea8-102">Initializes a new instance of the PrivateRegistryCredentials class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PrivateRegistryCredentials (string username, string password = null, Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference passwordSecretReference = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string username, string password, class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference passwordSecretReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (username As String, Optional password As String = null, Optional passwordSecretReference As KeyVaultSecretReference = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials : string * string * Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference -&gt; Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials" Usage="new Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials (username, password, passwordSecretReference)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="passwordSecretReference" Type="Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference" />
      </Parameters>
      <Docs>
        <param name="username"><span data-ttu-id="caea8-103">Der Benutzername für die Anmeldung.</span><span class="sxs-lookup"><span data-stu-id="caea8-103">User name to login.</span></span></param>
        <param name="password"><span data-ttu-id="caea8-104">Kennwort zum Anmelden.</span><span class="sxs-lookup"><span data-stu-id="caea8-104">Password to login.</span></span></param>
        <param name="passwordSecretReference"><span data-ttu-id="caea8-105">Gibt den Speicherort des Kennworts, die einen Key Vault geheimen Schlüssel ist.</span><span class="sxs-lookup"><span data-stu-id="caea8-105">Specifies the location of the password, which is a Key Vault Secret.</span></span></param>
        <summary>
            <span data-ttu-id="caea8-106">Initialisiert eine neue Instanz der PrivateRegistryCredentials-Klasse.</span><span class="sxs-lookup"><span data-stu-id="caea8-106">Initializes a new instance of the PrivateRegistryCredentials class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="caea8-107">Ruft ab oder legt das Kennwort für die Anmeldung.</span><span class="sxs-lookup"><span data-stu-id="caea8-107">Gets or sets password to login.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="caea8-108">Das Kennwort oder PasswordSecretReference muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="caea8-108">One of password or passwordSecretReference must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordSecretReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference PasswordSecretReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference PasswordSecretReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.PasswordSecretReference" />
      <MemberSignature Language="VB.NET" Value="Public Property PasswordSecretReference As KeyVaultSecretReference" />
      <MemberSignature Language="F#" Value="member this.PasswordSecretReference : Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.PasswordSecretReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passwordSecretReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="caea8-109">Gibt den Speicherort des Kennworts, das ein Schlüssel Vault Geheimnis ist, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="caea8-109">Gets or sets specifies the location of the password, which is a Key Vault Secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="caea8-110">Benutzer können ihre geheime Schlüssel in Azure KeyVault speichern und übergibt ihn dann an den Batch AI-Dienst für die Integration von KeyVault.</span><span class="sxs-lookup"><span data-stu-id="caea8-110">Users can store their secrets in Azure KeyVault and pass it to the Batch AI Service to integrate with KeyVault.</span></span> <span data-ttu-id="caea8-111">Das Kennwort oder PasswordSecretReference muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="caea8-111">One of password or passwordSecretReference must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="caea8-112">Ruft ab, oder legt Sie Benutzernamen, die Anmeldung fest.</span><span class="sxs-lookup"><span data-stu-id="caea8-112">Gets or sets user name to login.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="privateRegistryCredentials.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="caea8-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="caea8-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="caea8-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="caea8-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
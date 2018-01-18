<Type Name="AllowRule" FullName="Microsoft.ServiceBus.Messaging.AllowRule">
  <TypeSignature Language="C#" Value="public class AllowRule : Microsoft.ServiceBus.Messaging.AuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AllowRule extends Microsoft.ServiceBus.Messaging.AuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.AllowRule" />
  <TypeSignature Language="VB.NET" Value="Public Class AllowRule&#xA;Inherits AuthorizationRule" />
  <TypeSignature Language="F#" Value="type AllowRule = class&#xA;    inherit AuthorizationRule" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.AuthorizationRule</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="AllowRule", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="62f26-101">Stellt die Regel zum Zulassen des dar.</span><span class="sxs-lookup"><span data-stu-id="62f26-101">Represents the rule to allow.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AllowRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AllowRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="62f26-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.AllowRule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="62f26-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.AllowRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AllowRule (string issuerName, Microsoft.ServiceBus.Messaging.AllowRuleClaimType claimType, string claimValue, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string issuerName, valuetype Microsoft.ServiceBus.Messaging.AllowRuleClaimType claimType, string claimValue, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AllowRule.#ctor(System.String,Microsoft.ServiceBus.Messaging.AllowRuleClaimType,System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (issuerName As String, claimType As AllowRuleClaimType, claimValue As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.AllowRule : string * Microsoft.ServiceBus.Messaging.AllowRuleClaimType * string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.AllowRule" Usage="new Microsoft.ServiceBus.Messaging.AllowRule (issuerName, claimType, claimValue, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="claimType" Type="Microsoft.ServiceBus.Messaging.AllowRuleClaimType" />
        <Parameter Name="claimValue" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="62f26-103">Die <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.IssuerName" /> Name, der den Anspruchsaussteller.</span><span class="sxs-lookup"><span data-stu-id="62f26-103">The <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.IssuerName" /> name of the claim issuer.</span></span></param>
        <param name="claimType"><span data-ttu-id="62f26-104">Die <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.ClaimType" /> Typ des Anspruchs.</span><span class="sxs-lookup"><span data-stu-id="62f26-104">The <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.ClaimType" /> type of the claim.</span></span></param>
        <param name="claimValue"><span data-ttu-id="62f26-105">Die <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.ClaimValue" /> Wert des Anspruchs.</span><span class="sxs-lookup"><span data-stu-id="62f26-105">The <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.ClaimValue" /> value of the claim.</span></span></param>
        <param name="rights"><span data-ttu-id="62f26-106">Die Liste der möglichen <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.Rights" />.</span><span class="sxs-lookup"><span data-stu-id="62f26-106">The list of possible <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.Rights" />.</span></span></param>
        <summary><span data-ttu-id="62f26-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.AllowRule" />-Klasse mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="62f26-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.AllowRule" /> class with the specified parameters.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AllowRule (string issuerName, string claimType, string claimValue, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string issuerName, string claimType, string claimValue, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AllowRule.#ctor(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (issuerName As String, claimType As String, claimValue As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.AllowRule : string * string * string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.AllowRule" Usage="new Microsoft.ServiceBus.Messaging.AllowRule (issuerName, claimType, claimValue, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="claimType" Type="System.String" />
        <Parameter Name="claimValue" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="62f26-108">Die <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.IssuerName" /> Name, der den Anspruchsaussteller.</span><span class="sxs-lookup"><span data-stu-id="62f26-108">The <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.IssuerName" /> name of the claim issuer.</span></span></param>
        <param name="claimType"><span data-ttu-id="62f26-109">Die <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.ClaimType" /> Typ des Anspruchs.</span><span class="sxs-lookup"><span data-stu-id="62f26-109">The <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.ClaimType" /> type of the claim.</span></span></param>
        <param name="claimValue"><span data-ttu-id="62f26-110">Die <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.ClaimValue" /> Wert des Anspruchs.</span><span class="sxs-lookup"><span data-stu-id="62f26-110">The <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.ClaimValue" /> value of the claim.</span></span></param>
        <param name="rights"><span data-ttu-id="62f26-111">Die Liste der möglichen <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.Rights" />.</span><span class="sxs-lookup"><span data-stu-id="62f26-111">The list of possible <see cref="P:Microsoft.ServiceBus.Messaging.AuthorizationRule.Rights" />.</span></span></param>
        <summary><span data-ttu-id="62f26-112">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.AllowRule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="62f26-112">Initializes a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.AllowRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public override string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.AllowRule.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.ServiceBus.Messaging.AllowRule.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="62f26-113">Ruft ab, oder legt ihn fest Schlüssel zulassen Regelname.</span><span class="sxs-lookup"><span data-stu-id="62f26-113">Gets or sets the allow rule key name.</span></span></summary>
        <value><span data-ttu-id="62f26-114">Der zulassen Key Regelname.</span><span class="sxs-lookup"><span data-stu-id="62f26-114">The allow rule key name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
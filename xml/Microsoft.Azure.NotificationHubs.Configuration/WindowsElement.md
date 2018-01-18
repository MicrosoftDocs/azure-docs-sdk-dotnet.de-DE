<Type Name="WindowsElement" FullName="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement">
  <TypeSignature Language="C#" Value="public class WindowsElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type WindowsElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="fab8a-101">Stellt das Windows-Element für die Konfiguration von Servicebus.</span><span class="sxs-lookup"><span data-stu-id="fab8a-101">Represents the windows element for the configuration of the service bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (Microsoft.Azure.NotificationHubs.Configuration.WindowsElement source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class Microsoft.Azure.NotificationHubs.Configuration.WindowsElement source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.CopyFrom(Microsoft.Azure.NotificationHubs.Configuration.WindowsElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (source As WindowsElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : Microsoft.Azure.NotificationHubs.Configuration.WindowsElement -&gt; unit" Usage="windowsElement.CopyFrom source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fab8a-102">Das Windows-Element kopiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="fab8a-102">The windows element to copy.</span></span></param>
        <summary><span data-ttu-id="fab8a-103">Kopiert das angegebene Windows-Element in der aktuellen Instanz.</span><span class="sxs-lookup"><span data-stu-id="fab8a-103">Copies the specified windows element into the current instance.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Domain">
      <MemberSignature Language="C#" Value="public string Domain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Domain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Domain" />
      <MemberSignature Language="VB.NET" Value="Public Property Domain As String" />
      <MemberSignature Language="F#" Value="member this.Domain : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Domain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("domain", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fab8a-104">Ruft ab oder legt die Domäne.</span><span class="sxs-lookup"><span data-stu-id="fab8a-104">Gets or sets the domain.</span></span></summary>
        <value><span data-ttu-id="fab8a-105">Die Domäne.</span><span class="sxs-lookup"><span data-stu-id="fab8a-105">The domain.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("password", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fab8a-106">Ruft das Kennwort ab oder legt dieses fest.</span><span class="sxs-lookup"><span data-stu-id="fab8a-106">Gets or sets the password.</span></span></summary>
        <value><span data-ttu-id="fab8a-107">Das Kennwort.</span><span class="sxs-lookup"><span data-stu-id="fab8a-107">The password.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fab8a-108">Ruft ab oder legt die Auflistung von Konfigurationseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="fab8a-108">Gets or sets the collection of configuration properties.</span></span></summary>
        <value><span data-ttu-id="fab8a-109">Die Auflistung von Konfigurationseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="fab8a-109">The collection of configuration properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StsUris">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection StsUris { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection StsUris" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.StsUris" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property StsUris As StsUriElementCollection" />
      <MemberSignature Language="F#" Value="member this.StsUris : Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.StsUris" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("stsUris", IsDefaultCollection=false, IsRequired=true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Configuration.StsUriElementCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fab8a-110">Ruft ab oder legt die Auflistung der Sicherheitstokendienst (STS) URI.</span><span class="sxs-lookup"><span data-stu-id="fab8a-110">Gets or sets the collection of security token service (STS) URI.</span></span></summary>
        <value><span data-ttu-id="fab8a-111">Die Auflistung der Sicherheitstokendienst (STS) URI.</span><span class="sxs-lookup"><span data-stu-id="fab8a-111">The collection of security token service (STS) URI.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultCredentials">
      <MemberSignature Language="C#" Value="public bool UseDefaultCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.UseDefaultCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultCredentials As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultCredentials : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.UseDefaultCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("useDefaultCredentials", DefaultValue=Mono.Cecil.CustomAttributeArgument, IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fab8a-112">Ruft ab oder legt einen Wert, der angibt, ob die Standardanmeldeinformationen verwendet.</span><span class="sxs-lookup"><span data-stu-id="fab8a-112">Gets or sets a value that indicates whether to use default credentials.</span></span></summary>
        <value><span data-ttu-id="fab8a-113">"true", wenn die Standardanmeldeinformationen verwendet; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="fab8a-113">true if to use default credentials; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.WindowsElement.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("userName", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fab8a-114">Ruft ab oder legt den Benutzernamen fest.</span><span class="sxs-lookup"><span data-stu-id="fab8a-114">Gets or sets the username.</span></span></summary>
        <value><span data-ttu-id="fab8a-115">Der Benutzername.</span><span class="sxs-lookup"><span data-stu-id="fab8a-115">The username.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
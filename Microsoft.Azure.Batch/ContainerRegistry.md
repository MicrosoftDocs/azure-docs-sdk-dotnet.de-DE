<Type Name="ContainerRegistry" FullName="Microsoft.Azure.Batch.ContainerRegistry">
  <TypeSignature Language="C#" Value="public class ContainerRegistry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerRegistry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ContainerRegistry" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerRegistry" />
  <TypeSignature Language="F#" Value="type ContainerRegistry = class&#xA;    interface ITransportObjectProvider&lt;ContainerRegistry&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ed436-101">Eine private containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="ed436-101">A private container registry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerRegistry (string userName, string registryServer = null, string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userName, string registryServer, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ContainerRegistry.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (userName As String, Optional registryServer As String = null, Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ContainerRegistry : string * string * string -&gt; Microsoft.Azure.Batch.ContainerRegistry" Usage="new Microsoft.Azure.Batch.ContainerRegistry (userName, registryServer, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="registryServer" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userName"><span data-ttu-id="ed436-102">Der Benutzername, bei der Registrierungsserver anzumelden.</span><span class="sxs-lookup"><span data-stu-id="ed436-102">The user name to log into the registry server.</span></span></param>
        <param name="registryServer"><span data-ttu-id="ed436-103">Die Registrierungs-URL.</span><span class="sxs-lookup"><span data-stu-id="ed436-103">The registry URL.</span></span></param>
        <param name="password"><span data-ttu-id="ed436-104">Das Kennwort bei der Registrierungsserver anmelden.</span><span class="sxs-lookup"><span data-stu-id="ed436-104">The password to log into the registry server.</span></span></param>
        <summary>
            <span data-ttu-id="ed436-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ContainerRegistry" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ed436-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ContainerRegistry" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ContainerRegistry.Password" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string" Usage="Microsoft.Azure.Batch.ContainerRegistry.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed436-106">Ruft das Kennwort ab, bei der Registrierungsserver anzumelden.</span><span class="sxs-lookup"><span data-stu-id="ed436-106">Gets the password to log into the registry server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistryServer">
      <MemberSignature Language="C#" Value="public string RegistryServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistryServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ContainerRegistry.RegistryServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistryServer As String" />
      <MemberSignature Language="F#" Value="member this.RegistryServer : string" Usage="Microsoft.Azure.Batch.ContainerRegistry.RegistryServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed436-107">Ruft die Registrierungs-URL ab.</span><span class="sxs-lookup"><span data-stu-id="ed436-107">Gets the registry URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ed436-108">Wenn nicht angegeben, ist die Standardeinstellung "docker.io".</span><span class="sxs-lookup"><span data-stu-id="ed436-108">If omitted, the default is "docker.io".</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ContainerRegistry.UserName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string" Usage="Microsoft.Azure.Batch.ContainerRegistry.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed436-109">Ruft den Benutzernamen ab, bei der Registrierungsserver anzumelden.</span><span class="sxs-lookup"><span data-stu-id="ed436-109">Gets the user name to log into the registry server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
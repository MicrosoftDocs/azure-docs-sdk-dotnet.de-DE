<Type Name="RegistryPassword" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword">
  <TypeSignature Language="C#" Value="public class RegistryPassword" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegistryPassword extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword" />
  <TypeSignature Language="VB.NET" Value="Public Class RegistryPassword" />
  <TypeSignature Language="F#" Value="type RegistryPassword = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="360b4-101">Das Anmeldekennwort für die containerregistrierung.</span><span class="sxs-lookup"><span data-stu-id="360b4-101">The login password for the container registry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryPassword ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="360b4-102">Initialisiert eine neue Instanz der RegistryPassword-Klasse.</span><span class="sxs-lookup"><span data-stu-id="360b4-102">Initializes a new instance of the RegistryPassword class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryPassword (Nullable&lt;Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName&gt; name = null, string value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName&gt; name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword.#ctor(System.Nullable{Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As Nullable(Of PasswordName) = null, Optional value As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword : Nullable&lt;Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName&gt; * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword (name, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.Nullable&lt;Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName&gt;" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="360b4-103">Der Kennwortname.</span><span class="sxs-lookup"><span data-stu-id="360b4-103">The password name.</span></span> <span data-ttu-id="360b4-104">Folgende Werte sind möglich: "Kennwort", "password2"</span><span class="sxs-lookup"><span data-stu-id="360b4-104">Possible values include: 'password', 'password2'</span></span></param>
        <param name="value"><span data-ttu-id="360b4-105">Der Kennwortwert.</span><span class="sxs-lookup"><span data-stu-id="360b4-105">The password value.</span></span></param>
        <summary>
            <span data-ttu-id="360b4-106">Initialisiert eine neue Instanz der RegistryPassword-Klasse.</span><span class="sxs-lookup"><span data-stu-id="360b4-106">Initializes a new instance of the RegistryPassword class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName&gt; Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName&gt; Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As Nullable(Of PasswordName)" />
      <MemberSignature Language="F#" Value="member this.Name : Nullable&lt;Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="360b4-107">Ruft ab oder legt den Namen für das Kennwort fest.</span><span class="sxs-lookup"><span data-stu-id="360b4-107">Gets or sets the password name.</span></span> <span data-ttu-id="360b4-108">Folgende Werte sind möglich: "Kennwort", "password2"</span><span class="sxs-lookup"><span data-stu-id="360b4-108">Possible values include: 'password', 'password2'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryPassword.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="360b4-109">Ruft ab oder legt den Kennwortwert fest.</span><span class="sxs-lookup"><span data-stu-id="360b4-109">Gets or sets the password value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
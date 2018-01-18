<Type Name="ClientAssertion" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion">
  <TypeSignature Language="C#" Value="public sealed class ClientAssertion" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClientAssertion extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClientAssertion" />
  <TypeSignature Language="F#" Value="type ClientAssertion = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f82e3-101">Den Anmeldeinformationstyp, enthält eine Assertion des Typs "Urn: Ietf:params:oauth:token-Typ: Jwt".</span><span class="sxs-lookup"><span data-stu-id="f82e3-101">Credential type containing an assertion of type "urn:ietf:params:oauth:token-type:jwt".</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientAssertion (string clientId, string assertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string assertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, assertion As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion (clientId, assertion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="assertion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="f82e3-102">Der Bezeichner des Clients, die das Token anfordert.</span><span class="sxs-lookup"><span data-stu-id="f82e3-102">Identifier of the client requesting the token.</span></span></param>
        <param name="assertion"><span data-ttu-id="f82e3-103">Das Jwt als Anmeldeinformationen verwendet.</span><span class="sxs-lookup"><span data-stu-id="f82e3-103">The jwt used as credential.</span></span></param>
        <summary>
            <span data-ttu-id="f82e3-104">Konstruktor zum Erstellen von Anmeldeinformationen mit einem Jwt-Token als eine base64-codierte Url-Zeichenfolge codiert.</span><span class="sxs-lookup"><span data-stu-id="f82e3-104">Constructor to create credential with a jwt token encoded as a base64 url encoded string.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Assertion">
      <MemberSignature Language="C#" Value="public string Assertion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Assertion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.Assertion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Assertion As String" />
      <MemberSignature Language="F#" Value="member this.Assertion : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.Assertion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f82e3-105">Ruft die Assertion ab.</span><span class="sxs-lookup"><span data-stu-id="f82e3-105">Gets the assertion.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AssertionType">
      <MemberSignature Language="C#" Value="public string AssertionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AssertionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.AssertionType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AssertionType As String" />
      <MemberSignature Language="F#" Value="member this.AssertionType : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.AssertionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f82e3-106">Ruft den Typ der Assertion ab.</span><span class="sxs-lookup"><span data-stu-id="f82e3-106">Gets the assertion type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f82e3-107">Ruft den Bezeichner des Clients, die das Token anfordert.</span><span class="sxs-lookup"><span data-stu-id="f82e3-107">Gets the identifier of the client requesting the token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
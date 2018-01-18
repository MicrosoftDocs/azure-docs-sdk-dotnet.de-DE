<Type Name="AuthenticationMethodFactory" FullName="Microsoft.Azure.Devices.AuthenticationMethodFactory">
  <TypeSignature Language="C#" Value="public sealed class AuthenticationMethodFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AuthenticationMethodFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.AuthenticationMethodFactory" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AuthenticationMethodFactory" />
  <TypeSignature Language="F#" Value="type AuthenticationMethodFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="03268-101">Erstellt eine Instanz einer Implementierung der <see cref="T:Microsoft.Azure.Devices.IAuthenticationMethod" /> basierend auf bekannten Authentifizierungsparameter.</span><span class="sxs-lookup"><span data-stu-id="03268-101">Creates an instance of an implementation of <see cref="T:Microsoft.Azure.Devices.IAuthenticationMethod" /> based on known authentication parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationMethodFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.AuthenticationMethodFactory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAuthenticationWithSharedAccessPolicyKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.IAuthenticationMethod CreateAuthenticationWithSharedAccessPolicyKey (string policyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.IAuthenticationMethod CreateAuthenticationWithSharedAccessPolicyKey(string policyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.AuthenticationMethodFactory.CreateAuthenticationWithSharedAccessPolicyKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAuthenticationWithSharedAccessPolicyKey (policyName As String, key As String) As IAuthenticationMethod" />
      <MemberSignature Language="F#" Value="static member CreateAuthenticationWithSharedAccessPolicyKey : string * string -&gt; Microsoft.Azure.Devices.IAuthenticationMethod" Usage="Microsoft.Azure.Devices.AuthenticationMethodFactory.CreateAuthenticationWithSharedAccessPolicyKey (policyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IAuthenticationMethod</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policyName"> <span data-ttu-id="03268-102">PolicyName</span><span class="sxs-lookup"><span data-stu-id="03268-102">PolicyName</span></span> </param>
        <param name="key"> <span data-ttu-id="03268-103">SharedAccessKeyValue</span><span class="sxs-lookup"><span data-stu-id="03268-103">SharedAccessKeyValue</span></span> </param>
        <summary>
             <span data-ttu-id="03268-104">Factorymethode zum Erstellen eines Objekts ServiceAuthenticationWithSharedAccessPolicyKey</span><span class="sxs-lookup"><span data-stu-id="03268-104">Factory method to create a ServiceAuthenticationWithSharedAccessPolicyKey object</span></span>
            </summary>
        <returns> <span data-ttu-id="03268-105">ein Objekt AuthenticationMethod</span><span class="sxs-lookup"><span data-stu-id="03268-105">an AuthenticationMethod object</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAuthenticationWithSharedAccessPolicyToken">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.IAuthenticationMethod CreateAuthenticationWithSharedAccessPolicyToken (string policyName, string token);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.IAuthenticationMethod CreateAuthenticationWithSharedAccessPolicyToken(string policyName, string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.AuthenticationMethodFactory.CreateAuthenticationWithSharedAccessPolicyToken(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAuthenticationWithSharedAccessPolicyToken (policyName As String, token As String) As IAuthenticationMethod" />
      <MemberSignature Language="F#" Value="static member CreateAuthenticationWithSharedAccessPolicyToken : string * string -&gt; Microsoft.Azure.Devices.IAuthenticationMethod" Usage="Microsoft.Azure.Devices.AuthenticationMethodFactory.CreateAuthenticationWithSharedAccessPolicyToken (policyName, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IAuthenticationMethod</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policyName"> <span data-ttu-id="03268-106">PolicyName</span><span class="sxs-lookup"><span data-stu-id="03268-106">PolicyName</span></span> </param>
        <param name="token"> <span data-ttu-id="03268-107">SharedAccessSignatureToken</span><span class="sxs-lookup"><span data-stu-id="03268-107">SharedAccessSignatureToken</span></span> </param>
        <summary>
             <span data-ttu-id="03268-108">Factorymethode zum Erstellen eines Objekts ServiceAuthenticationWithSharedAccessPolicyToken</span><span class="sxs-lookup"><span data-stu-id="03268-108">Factory method to create a ServiceAuthenticationWithSharedAccessPolicyToken object</span></span>
            </summary>
        <returns> <span data-ttu-id="03268-109">ein Objekt AuthenticationMethod</span><span class="sxs-lookup"><span data-stu-id="03268-109">an AuthenticationMethod object</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="SecureClientSecret" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret">
  <TypeSignature Language="C#" Value="public class SecureClientSecret : Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecureClientSecret extends System.Object implements class Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret" />
  <TypeSignature Language="VB.NET" Value="Public Class SecureClientSecret&#xA;Implements ISecureClientSecret" />
  <TypeSignature Language="F#" Value="type SecureClientSecret = class&#xA;    interface ISecureClientSecret" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5795b-101">Diese Klasse ermöglicht es, den geheimen Clientschlüssel als SecureString an die API übergeben.</span><span class="sxs-lookup"><span data-stu-id="5795b-101">This class allows to pass client secret as a SecureString to the API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecureClientSecret (System.Security.SecureString secret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Security.SecureString secret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret.#ctor(System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (secret As SecureString)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret : System.Security.SecureString -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret secret" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secret" Type="System.Security.SecureString" />
      </Parameters>
      <Docs>
        <param name="secret"><span data-ttu-id="5795b-102">SecureString geheime Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="5795b-102">SecureString secret.</span></span> <span data-ttu-id="5795b-103">Erforderlich und darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="5795b-103">Required and cannot be null.</span></span></param>
        <summary>
            <span data-ttu-id="5795b-104">Erforderliche Konstruktor</span><span class="sxs-lookup"><span data-stu-id="5795b-104">Required Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyTo">
      <MemberSignature Language="C#" Value="public void ApplyTo (System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ApplyTo(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.SecureClientSecret.ApplyTo(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ApplyTo (parameters As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="abstract member ApplyTo : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit&#xA;override this.ApplyTo : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="secureClientSecret.ApplyTo parameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret.ApplyTo(System.Collections.Generic.IDictionary{System.String,System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="parameters"><span data-ttu-id="5795b-105">Wörterbuch auf den Securestring angewendet wird, um an den Server gesendet werden</span><span class="sxs-lookup"><span data-stu-id="5795b-105">Dictionary to which the securestring is applied to be sent to server</span></span></param>
        <summary>
            <span data-ttu-id="5795b-106">Das Wörterbuch gilt den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="5795b-106">Applies the secret to the dictionary.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
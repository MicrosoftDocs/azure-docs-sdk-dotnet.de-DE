<Type Name="JsonSecurityToken" FullName="Microsoft.Azure.EventHubs.JsonSecurityToken">
  <TypeSignature Language="C#" Value="public class JsonSecurityToken : Microsoft.Azure.EventHubs.SecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JsonSecurityToken extends Microsoft.Azure.EventHubs.SecurityToken" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.JsonSecurityToken" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonSecurityToken&#xA;Inherits SecurityToken" />
  <TypeSignature Language="F#" Value="type JsonSecurityToken = class&#xA;    inherit SecurityToken" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.SecurityToken</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="738a6-101">SecurityToken erweitert für JWT-spezifischen Eigenschaften</span><span class="sxs-lookup"><span data-stu-id="738a6-101">Extends SecurityToken for JWT specific properties</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonSecurityToken (string rawToken, string audience);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string rawToken, string audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.JsonSecurityToken.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rawToken As String, audience As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.JsonSecurityToken : string * string -&gt; Microsoft.Azure.EventHubs.JsonSecurityToken" Usage="new Microsoft.Azure.EventHubs.JsonSecurityToken (rawToken, audience)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rawToken" Type="System.String" />
        <Parameter Name="audience" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rawToken"><span data-ttu-id="738a6-102">JSON-Webtoken rohzeichenfolge</span><span class="sxs-lookup"><span data-stu-id="738a6-102">Raw JSON Web Token string</span></span></param>
        <param name="audience"><span data-ttu-id="738a6-103">Die Zielgruppe</span><span class="sxs-lookup"><span data-stu-id="738a6-103">The audience</span></span></param>
        <summary>
            <span data-ttu-id="738a6-104">Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.EventHubs.JsonSecurityToken" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="738a6-104">Creates a new instance of the <see cref="T:Microsoft.Azure.EventHubs.JsonSecurityToken" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
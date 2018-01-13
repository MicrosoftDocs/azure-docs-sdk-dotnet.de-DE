<Type Name="SecurityToken" FullName="Microsoft.Azure.Relay.SecurityToken">
  <TypeSignature Language="C#" Value="public class SecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityToken extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.SecurityToken" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityToken" />
  <TypeSignature Language="F#" Value="type SecurityToken = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="919dd-101">Enthält Informationen zu der ein Sicherheitstoken, z. B. Zielgruppe, Ablaufzeit und die token-Zeichenfolgenwert.</span><span class="sxs-lookup"><span data-stu-id="919dd-101">Provides information about a security token such as audience, expiry time, and the string token value.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SecurityToken (string tokenString, string audienceFieldName, string expiresOnFieldName, string keyValueSeparator, string pairSeparator);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string tokenString, string audienceFieldName, string expiresOnFieldName, string keyValueSeparator, string pairSeparator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.SecurityToken.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (tokenString As String, audienceFieldName As String, expiresOnFieldName As String, keyValueSeparator As String, pairSeparator As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.SecurityToken : string * string * string * string * string -&gt; Microsoft.Azure.Relay.SecurityToken" Usage="new Microsoft.Azure.Relay.SecurityToken (tokenString, audienceFieldName, expiresOnFieldName, keyValueSeparator, pairSeparator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="audienceFieldName" Type="System.String" />
        <Parameter Name="expiresOnFieldName" Type="System.String" />
        <Parameter Name="keyValueSeparator" Type="System.String" />
        <Parameter Name="pairSeparator" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="919dd-102">Ein Token im Zeichenfolgenformat.</span><span class="sxs-lookup"><span data-stu-id="919dd-102">A token in string format.</span></span></param>
        <param name="audienceFieldName"><span data-ttu-id="919dd-103">Der Schlüsselname für das Feld Zielgruppe.</span><span class="sxs-lookup"><span data-stu-id="919dd-103">The key name for the audience field.</span></span></param>
        <param name="expiresOnFieldName"><span data-ttu-id="919dd-104">Die Schlüsselnamen für die läuft ab am Feld.</span><span class="sxs-lookup"><span data-stu-id="919dd-104">The key name for the expires on field.</span></span></param>
        <param name="keyValueSeparator"><span data-ttu-id="919dd-105">Das Trennzeichen zwischen den Schlüssel und Werte.</span><span class="sxs-lookup"><span data-stu-id="919dd-105">The separator between keys and values.</span></span></param>
        <param name="pairSeparator"><span data-ttu-id="919dd-106">Das Trennzeichen zwischen den anderen Schlüssel/Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="919dd-106">The separator between different key/value pairs.</span></span></param>
        <summary>
            <span data-ttu-id="919dd-107">Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.SecurityToken" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="919dd-107">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.SecurityToken" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Audience">
      <MemberSignature Language="C#" Value="public string Audience { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Audience" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.SecurityToken.Audience" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Audience As String" />
      <MemberSignature Language="F#" Value="member this.Audience : string" Usage="Microsoft.Azure.Relay.SecurityToken.Audience" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="919dd-108">Ruft die Zielgruppe dieses Tokens ab.</span><span class="sxs-lookup"><span data-stu-id="919dd-108">Gets the audience of this token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.SecurityToken.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.Azure.Relay.SecurityToken.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="919dd-109">Ruft die Ablaufzeit dieses Tokens ab.</span><span class="sxs-lookup"><span data-stu-id="919dd-109">Gets the expiration time of this token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenString">
      <MemberSignature Language="C#" Value="public string TokenString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.SecurityToken.TokenString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenString As String" />
      <MemberSignature Language="F#" Value="member this.TokenString : string" Usage="Microsoft.Azure.Relay.SecurityToken.TokenString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="919dd-110">Ruft die tatsächliche Token als Zeichenfolge ab.</span><span class="sxs-lookup"><span data-stu-id="919dd-110">Gets the actual token as a string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
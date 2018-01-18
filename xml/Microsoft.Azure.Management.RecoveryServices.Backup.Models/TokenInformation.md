<Type Name="TokenInformation" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation">
  <TypeSignature Language="C#" Value="public class TokenInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TokenInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TokenInformation" />
  <TypeSignature Language="F#" Value="type TokenInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c59a1-101">Die Details der Tokeninformationen.</span><span class="sxs-lookup"><span data-stu-id="c59a1-101">The token information details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c59a1-102">Initialisiert eine neue Instanz der TokenInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c59a1-102">Initializes a new instance of the TokenInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenInformation (string token = null, Nullable&lt;long&gt; expiryTimeInUtcTicks = null, string securityPIN = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string token, valuetype System.Nullable`1&lt;int64&gt; expiryTimeInUtcTicks, string securityPIN) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.#ctor(System.String,System.Nullable{System.Int64},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional token As String = null, Optional expiryTimeInUtcTicks As Nullable(Of Long) = null, Optional securityPIN As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation : string * Nullable&lt;int64&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation (token, expiryTimeInUtcTicks, securityPIN)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="expiryTimeInUtcTicks" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="securityPIN" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="c59a1-103">Tokenwert.</span><span class="sxs-lookup"><span data-stu-id="c59a1-103">Token value.</span></span></param>
        <param name="expiryTimeInUtcTicks"><span data-ttu-id="c59a1-104">Die Ablaufzeit des Tokens.</span><span class="sxs-lookup"><span data-stu-id="c59a1-104">Expiry time of token.</span></span></param>
        <param name="securityPIN"><span data-ttu-id="c59a1-105">Sicherheits-PIN</span><span class="sxs-lookup"><span data-stu-id="c59a1-105">Security PIN</span></span></param>
        <summary>
            <span data-ttu-id="c59a1-106">Initialisiert eine neue Instanz der TokenInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c59a1-106">Initializes a new instance of the TokenInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTimeInUtcTicks">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ExpiryTimeInUtcTicks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ExpiryTimeInUtcTicks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.ExpiryTimeInUtcTicks" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTimeInUtcTicks As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ExpiryTimeInUtcTicks : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.ExpiryTimeInUtcTicks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expiryTimeInUtcTicks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c59a1-107">Ruft ab oder legt die Ablaufzeit des Tokens.</span><span class="sxs-lookup"><span data-stu-id="c59a1-107">Gets or sets expiry time of token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityPIN">
      <MemberSignature Language="C#" Value="public string SecurityPIN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecurityPIN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.SecurityPIN" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityPIN As String" />
      <MemberSignature Language="F#" Value="member this.SecurityPIN : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.SecurityPIN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="securityPIN")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c59a1-108">Ruft ab oder legt ihn fest Sicherheits-PIN</span><span class="sxs-lookup"><span data-stu-id="c59a1-108">Gets or sets security PIN</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="token")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c59a1-109">Ruft ab, oder legt ihn fest-Tokenwert.</span><span class="sxs-lookup"><span data-stu-id="c59a1-109">Gets or sets token value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
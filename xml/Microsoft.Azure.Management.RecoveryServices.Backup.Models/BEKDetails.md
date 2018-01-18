<Type Name="BEKDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails">
  <TypeSignature Language="C#" Value="public class BEKDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BEKDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class BEKDetails" />
  <TypeSignature Language="F#" Value="type BEKDetails = class" />
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
            <span data-ttu-id="d963d-101">BEK ist Bitlocker Encrpytion Key.</span><span class="sxs-lookup"><span data-stu-id="d963d-101">BEK is bitlocker encrpytion key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BEKDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d963d-102">Initialisiert eine neue Instanz der BEKDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d963d-102">Initializes a new instance of the BEKDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BEKDetails (string secretUrl = null, string secretVaultId = null, string secretData = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string secretUrl, string secretVaultId, string secretData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional secretUrl As String = null, Optional secretVaultId As String = null, Optional secretData As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails (secretUrl, secretVaultId, secretData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secretUrl" Type="System.String" />
        <Parameter Name="secretVaultId" Type="System.String" />
        <Parameter Name="secretData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="secretUrl"><span data-ttu-id="d963d-103">Geheime Schlüssel ist BEK.</span><span class="sxs-lookup"><span data-stu-id="d963d-103">Secret is BEK.</span></span></param>
        <param name="secretVaultId"><span data-ttu-id="d963d-104">ID der Schlüsseltresor, in dem dieser geheime Schlüssel gespeichert ist.</span><span class="sxs-lookup"><span data-stu-id="d963d-104">ID of the Key Vault where this Secret is stored.</span></span></param>
        <param name="secretData"><span data-ttu-id="d963d-105">BEK Daten.</span><span class="sxs-lookup"><span data-stu-id="d963d-105">BEK data.</span></span></param>
        <summary>
            <span data-ttu-id="d963d-106">Initialisiert eine neue Instanz der BEKDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d963d-106">Initializes a new instance of the BEKDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretData">
      <MemberSignature Language="C#" Value="public string SecretData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretData" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretData As String" />
      <MemberSignature Language="F#" Value="member this.SecretData : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d963d-107">Ruft ab oder legt BEK Daten.</span><span class="sxs-lookup"><span data-stu-id="d963d-107">Gets or sets BEK data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretUrl">
      <MemberSignature Language="C#" Value="public string SecretUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretUrl As String" />
      <MemberSignature Language="F#" Value="member this.SecretUrl : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d963d-108">Ruft ab oder legt ihn fest geheime Schlüssel ist BEK.</span><span class="sxs-lookup"><span data-stu-id="d963d-108">Gets or sets secret is BEK.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretVaultId">
      <MemberSignature Language="C#" Value="public string SecretVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretVaultId As String" />
      <MemberSignature Language="F#" Value="member this.SecretVaultId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d963d-109">Ruft ab, oder legt ihn fest-ID des Schlüsseltresor, in dem dieser geheime Schlüssel gespeichert ist.</span><span class="sxs-lookup"><span data-stu-id="d963d-109">Gets or sets ID of the Key Vault where this Secret is stored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
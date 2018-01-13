<Type Name="SecurityProviderTpm" FullName="Microsoft.Azure.Devices.Shared.SecurityProviderTpm">
  <TypeSignature Language="C#" Value="public abstract class SecurityProviderTpm : Microsoft.Azure.Devices.Shared.SecurityProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SecurityProviderTpm extends Microsoft.Azure.Devices.Shared.SecurityProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.SecurityProviderTpm" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SecurityProviderTpm&#xA;Inherits SecurityProvider" />
  <TypeSignature Language="F#" Value="type SecurityProviderTpm = class&#xA;    inherit SecurityProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.Shared.SecurityProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="94d2b-101">Die für TPM Hardwaresicherheitsmodulen Gerät Security Provider-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="94d2b-101">The Device Security Provider interface for TPM Hardware Security Modules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityProviderTpm (string registrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (registrationId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Shared.SecurityProviderTpm : string -&gt; Microsoft.Azure.Devices.Shared.SecurityProviderTpm" Usage="new Microsoft.Azure.Devices.Shared.SecurityProviderTpm registrationId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId"><span data-ttu-id="94d2b-102">Die Provisioning-Dienst Registrierungs-ID für dieses Gerät.</span><span class="sxs-lookup"><span data-stu-id="94d2b-102">The Provisioning service Registration ID for this device.</span></span></param>
        <summary>
            <span data-ttu-id="94d2b-103">Initialisiert eine neue Instanz der SecurityProviderTpm-Klasse.</span><span class="sxs-lookup"><span data-stu-id="94d2b-103">Initializes a new instance of the SecurityProviderTpm class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivateIdentityKey">
      <MemberSignature Language="C#" Value="public abstract void ActivateIdentityKey (byte[] encryptedKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ActivateIdentityKey(unsigned int8[] encryptedKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.ActivateIdentityKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub ActivateIdentityKey (encryptedKey As Byte())" />
      <MemberSignature Language="F#" Value="abstract member ActivateIdentityKey : byte[] -&gt; unit" Usage="securityProviderTpm.ActivateIdentityKey encryptedKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptedKey" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="encryptedKey"><span data-ttu-id="94d2b-104">Der verschlüsselte Identitätsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="94d2b-104">The encrypted identity key.</span></span></param>
        <summary>
            <span data-ttu-id="94d2b-105">Aktiviert einen Identitätsschlüssel innerhalb des TPM-Geräts an.</span><span class="sxs-lookup"><span data-stu-id="94d2b-105">Activates an identity key within the TPM device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndorsementKey">
      <MemberSignature Language="C#" Value="public abstract byte[] GetEndorsementKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] GetEndorsementKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.GetEndorsementKey" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetEndorsementKey () As Byte()" />
      <MemberSignature Language="F#" Value="abstract member GetEndorsementKey : unit -&gt; byte[]" Usage="securityProviderTpm.GetEndorsementKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94d2b-106">Ruft die Base64-codierte EndorsementKey.</span><span class="sxs-lookup"><span data-stu-id="94d2b-106">Gets the Base64 encoded EndorsementKey.</span></span>
            </summary>
        <returns><span data-ttu-id="94d2b-107">Base64-codierte EK.</span><span class="sxs-lookup"><span data-stu-id="94d2b-107">Base64 encoded EK.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationID">
      <MemberSignature Language="C#" Value="public override string GetRegistrationID ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string GetRegistrationID() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.GetRegistrationID" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetRegistrationID () As String" />
      <MemberSignature Language="F#" Value="override this.GetRegistrationID : unit -&gt; string" Usage="securityProviderTpm.GetRegistrationID " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94d2b-108">Ruft die Registrierungs-ID, die während der Registrierung des Geräts verwendet.</span><span class="sxs-lookup"><span data-stu-id="94d2b-108">Gets the Registration ID used during device enrollment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageRootKey">
      <MemberSignature Language="C#" Value="public abstract byte[] GetStorageRootKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] GetStorageRootKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.GetStorageRootKey" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetStorageRootKey () As Byte()" />
      <MemberSignature Language="F#" Value="abstract member GetStorageRootKey : unit -&gt; byte[]" Usage="securityProviderTpm.GetStorageRootKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94d2b-109">Ruft die Base64-codierte StorageRootKey.</span><span class="sxs-lookup"><span data-stu-id="94d2b-109">Gets the Base64 encoded StorageRootKey.</span></span>
            </summary>
        <returns><span data-ttu-id="94d2b-110">Base64-codierte SRK.</span><span class="sxs-lookup"><span data-stu-id="94d2b-110">Base64 encoded SRK.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sign">
      <MemberSignature Language="C#" Value="public abstract byte[] Sign (byte[] data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] Sign(unsigned int8[] data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.Sign(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Sign (data As Byte()) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member Sign : byte[] -&gt; byte[]" Usage="securityProviderTpm.Sign data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="94d2b-111">Die zu signierenden Daten.</span><span class="sxs-lookup"><span data-stu-id="94d2b-111">The data to be signed.</span></span></param>
        <summary>
            <span data-ttu-id="94d2b-112">Signiert die Daten mithilfe des zuvor aktivierten Identitätsschlüssels.</span><span class="sxs-lookup"><span data-stu-id="94d2b-112">Signs the data using the previously activated identity key.</span></span>
            </summary>
        <returns><span data-ttu-id="94d2b-113">Die signierten Daten.</span><span class="sxs-lookup"><span data-stu-id="94d2b-113">The signed data.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
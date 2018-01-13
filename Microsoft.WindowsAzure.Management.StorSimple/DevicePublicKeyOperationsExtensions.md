<Type Name="DevicePublicKeyOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DevicePublicKeyOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DevicePublicKeyOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DevicePublicKeyOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DevicePublicKeyOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1824e-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="1824e-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions.Get (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1824e-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations.</span><span class="sxs-lookup"><span data-stu-id="1824e-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="1824e-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1824e-103">Required.</span></span> <span data-ttu-id="1824e-104">Die Geräte-Id, die wir den öffentlichen Schlüssel des Geräts abgerufen müssen.</span><span class="sxs-lookup"><span data-stu-id="1824e-104">The Device Id for which we need to Fetch the Device Public Key</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="1824e-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1824e-105">Required.</span></span> <span data-ttu-id="1824e-106">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="1824e-106">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="1824e-107">Das Antwort-Modell für PublicKey-Gerät.</span><span class="sxs-lookup"><span data-stu-id="1824e-107">The response model for Device PublicKey.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions.GetAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1824e-108">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations.</span><span class="sxs-lookup"><span data-stu-id="1824e-108">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="1824e-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1824e-109">Required.</span></span> <span data-ttu-id="1824e-110">Die Geräte-Id, die wir den öffentlichen Schlüssel des Geräts abgerufen müssen.</span><span class="sxs-lookup"><span data-stu-id="1824e-110">The Device Id for which we need to Fetch the Device Public Key</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="1824e-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1824e-111">Required.</span></span> <span data-ttu-id="1824e-112">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="1824e-112">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="1824e-113">Das Antwort-Modell für PublicKey-Gerät.</span><span class="sxs-lookup"><span data-stu-id="1824e-113">The response model for Device PublicKey.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="TargetEligibilityErrorMessage" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage">
  <TypeSignature Language="C#" Value="public class TargetEligibilityErrorMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TargetEligibilityErrorMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class TargetEligibilityErrorMessage" />
  <TypeSignature Language="F#" Value="type TargetEligibilityErrorMessage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="71655-101">Der Fehler/einer Warnung Nachricht aufgrund von der das Gerät als ein Zielgerät Failover nicht geeignet ist.</span><span class="sxs-lookup"><span data-stu-id="71655-101">The error/warning message due to which the device is ineligible as a failover target device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TargetEligibilityErrorMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="71655-102">Initialisiert eine neue Instanz der TargetEligibilityErrorMessage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="71655-102">Initializes a new instance of the TargetEligibilityErrorMessage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TargetEligibilityErrorMessage (string message = null, string resolution = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; resultCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, string resolution, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; resultCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional message As String = null, Optional resolution As String = null, Optional resultCode As Nullable(Of TargetEligibilityResultCode) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage : string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage (message, resolution, resultCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="resolution" Type="System.String" />
        <Parameter Name="resultCode" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt;" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="71655-103">Die lokalisierte Fehlermeldung besagt den Grund, warum das Gerät nicht als Zielgerät geeignet sind.</span><span class="sxs-lookup"><span data-stu-id="71655-103">The localized error message stating the reason why the device is not eligible as a target device.</span></span></param>
        <param name="resolution"><span data-ttu-id="71655-104">Die lokalisierte Auflösung Meldung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="71655-104">The localized resolution message for the error.</span></span></param>
        <param name="resultCode"><span data-ttu-id="71655-105">Das Resultat den Code für den Fehler, die aufgrund von dem das Gerät nicht als Zielgerät Failover qualifiziert.</span><span class="sxs-lookup"><span data-stu-id="71655-105">The result code for the error, due to which the device does not qualify as a failover target device.</span></span>
            <span data-ttu-id="71655-106">Folgende Werte sind möglich: "TargetAndSourceCannotBeSameError", "TargetIsNotOnlineError", "TargetSourceIncompatibleVersionError", "LocalToTieredVolumesConversionWarning", "TargetInsufficientCapacityError", " TargetInsufficientLocalVolumeMemoryError ","TargetInsufficientTieredVolumeMemoryError"</span><span class="sxs-lookup"><span data-stu-id="71655-106">Possible values include: 'TargetAndSourceCannotBeSameError', 'TargetIsNotOnlineError', 'TargetSourceIncompatibleVersionError', 'LocalToTieredVolumesConversionWarning', 'TargetInsufficientCapacityError', 'TargetInsufficientLocalVolumeMemoryError', 'TargetInsufficientTieredVolumeMemoryError'</span></span></param>
        <summary>
            <span data-ttu-id="71655-107">Initialisiert eine neue Instanz der TargetEligibilityErrorMessage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="71655-107">Initializes a new instance of the TargetEligibilityErrorMessage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71655-108">Ruft ab oder legt der lokalisierten Fehlermeldung den Grund, warum das Gerät nicht als Zielgerät geeignet sind.</span><span class="sxs-lookup"><span data-stu-id="71655-108">Gets or sets the localized error message stating the reason why the device is not eligible as a target device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resolution">
      <MemberSignature Language="C#" Value="public string Resolution { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resolution" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.Resolution" />
      <MemberSignature Language="VB.NET" Value="Public Property Resolution As String" />
      <MemberSignature Language="F#" Value="member this.Resolution : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.Resolution" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resolution")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71655-109">Ermittelt oder definiert die lokalisierten Auflösung Meldung des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="71655-109">Gets or sets the localized resolution message for the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; ResultCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; ResultCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.ResultCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultCode As Nullable(Of TargetEligibilityResultCode)" />
      <MemberSignature Language="F#" Value="member this.ResultCode : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.ResultCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resultCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71655-110">Abrufen oder festlegen den Ergebniscode für den Fehler, die aufgrund von dem das Gerät nicht als Zielgerät Failover qualifiziert.</span><span class="sxs-lookup"><span data-stu-id="71655-110">Gets or sets the result code for the error, due to which the device does not qualify as a failover target device.</span></span> <span data-ttu-id="71655-111">Folgende Werte sind möglich: "TargetAndSourceCannotBeSameError", "TargetIsNotOnlineError", "TargetSourceIncompatibleVersionError", "LocalToTieredVolumesConversionWarning", "TargetInsufficientCapacityError", " TargetInsufficientLocalVolumeMemoryError ","TargetInsufficientTieredVolumeMemoryError"</span><span class="sxs-lookup"><span data-stu-id="71655-111">Possible values include: 'TargetAndSourceCannotBeSameError', 'TargetIsNotOnlineError', 'TargetSourceIncompatibleVersionError', 'LocalToTieredVolumesConversionWarning', 'TargetInsufficientCapacityError', 'TargetInsufficientLocalVolumeMemoryError', 'TargetInsufficientTieredVolumeMemoryError'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="RemoteManagementSettingsPatch" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch">
  <TypeSignature Language="C#" Value="public class RemoteManagementSettingsPatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RemoteManagementSettingsPatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch" />
  <TypeSignature Language="VB.NET" Value="Public Class RemoteManagementSettingsPatch" />
  <TypeSignature Language="F#" Value="type RemoteManagementSettingsPatch = class" />
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
            <span data-ttu-id="25d17-101">Die Einstellungen für die Remoteverwaltung Updatemodus des Geräts.</span><span class="sxs-lookup"><span data-stu-id="25d17-101">The settings for updating remote management mode of the device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteManagementSettingsPatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25d17-102">Initialisiert eine neue Instanz der RemoteManagementSettingsPatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="25d17-102">Initializes a new instance of the RemoteManagementSettingsPatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteManagementSettingsPatch (Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration remoteManagementMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration remoteManagementMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (remoteManagementMode As RemoteManagementModeConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch : Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch remoteManagementMode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="remoteManagementMode" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration" />
      </Parameters>
      <Docs>
        <param name="remoteManagementMode"><span data-ttu-id="25d17-103">Der remote-Management-Modus.</span><span class="sxs-lookup"><span data-stu-id="25d17-103">The remote management mode.</span></span>
            <span data-ttu-id="25d17-104">Folgende Werte sind möglich: "Unknown", "Deaktiviert", "HttpsEnabled", "HttpsAndHttpEnabled"</span><span class="sxs-lookup"><span data-stu-id="25d17-104">Possible values include: 'Unknown', 'Disabled', 'HttpsEnabled', 'HttpsAndHttpEnabled'</span></span></param>
        <summary>
            <span data-ttu-id="25d17-105">Initialisiert eine neue Instanz der RemoteManagementSettingsPatch-Klasse.</span><span class="sxs-lookup"><span data-stu-id="25d17-105">Initializes a new instance of the RemoteManagementSettingsPatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteManagementMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration RemoteManagementMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration RemoteManagementMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch.RemoteManagementMode" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteManagementMode As RemoteManagementModeConfiguration" />
      <MemberSignature Language="F#" Value="member this.RemoteManagementMode : Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch.RemoteManagementMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteManagementMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementModeConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d17-106">Ruft ab oder legt den Modus für die Remoteverwaltung.</span><span class="sxs-lookup"><span data-stu-id="25d17-106">Gets or sets the remote management mode.</span></span> <span data-ttu-id="25d17-107">Folgende Werte sind möglich: "Unknown", "Deaktiviert", "HttpsEnabled", "HttpsAndHttpEnabled"</span><span class="sxs-lookup"><span data-stu-id="25d17-107">Possible values include: 'Unknown', 'Disabled', 'HttpsEnabled', 'HttpsAndHttpEnabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="remoteManagementSettingsPatch.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25d17-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="25d17-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="25d17-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="25d17-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
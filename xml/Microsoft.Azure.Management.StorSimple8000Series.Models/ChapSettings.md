<Type Name="ChapSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings">
  <TypeSignature Language="C#" Value="public class ChapSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChapSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ChapSettings" />
  <TypeSignature Language="F#" Value="type ChapSettings = class" />
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
            <span data-ttu-id="3a1ec-101">Die Einstellungen des Challenge Handshake Authentication-Protokoll (CHAP).</span><span class="sxs-lookup"><span data-stu-id="3a1ec-101">The Challenge-Handshake Authentication Protocol (CHAP) settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChapSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3a1ec-102">Initialisiert eine neue Instanz der ChapSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-102">Initializes a new instance of the ChapSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChapSettings (string initiatorUser = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret initiatorSecret = null, string targetUser = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret targetSecret = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string initiatorUser, class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret initiatorSecret, string targetUser, class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret targetSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional initiatorUser As String = null, Optional initiatorSecret As AsymmetricEncryptedSecret = null, Optional targetUser As String = null, Optional targetSecret As AsymmetricEncryptedSecret = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings (initiatorUser, initiatorSecret, targetUser, targetSecret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="initiatorUser" Type="System.String" />
        <Parameter Name="initiatorSecret" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
        <Parameter Name="targetUser" Type="System.String" />
        <Parameter Name="targetSecret" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
      </Parameters>
      <Docs>
        <param name="initiatorUser"><span data-ttu-id="3a1ec-103">Der Benutzer für den CHAP-Initiator.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-103">The CHAP initiator user.</span></span></param>
        <param name="initiatorSecret"><span data-ttu-id="3a1ec-104">Das CHAP Initiator-Kennwort.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-104">The CHAP initiator secret.</span></span></param>
        <param name="targetUser"><span data-ttu-id="3a1ec-105">Der Benutzer für den CHAP-Ziel.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-105">The CHAP target user.</span></span></param>
        <param name="targetSecret"><span data-ttu-id="3a1ec-106">Der Zielschlüssel.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-106">The target secret.</span></span></param>
        <summary>
            <span data-ttu-id="3a1ec-107">Initialisiert eine neue Instanz der ChapSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-107">Initializes a new instance of the ChapSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitiatorSecret">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret InitiatorSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret InitiatorSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.InitiatorSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property InitiatorSecret As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.InitiatorSecret : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.InitiatorSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="initiatorSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a1ec-108">Ruft ab oder legt das CHAP Initiator-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-108">Gets or sets the CHAP initiator secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitiatorUser">
      <MemberSignature Language="C#" Value="public string InitiatorUser { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InitiatorUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.InitiatorUser" />
      <MemberSignature Language="VB.NET" Value="Public Property InitiatorUser As String" />
      <MemberSignature Language="F#" Value="member this.InitiatorUser : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.InitiatorUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="initiatorUser")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a1ec-109">Ruft ab oder legt das CHAP Initiator-Benutzers fest.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-109">Gets or sets the CHAP initiator user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetSecret">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret TargetSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret TargetSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.TargetSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetSecret As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.TargetSecret : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.TargetSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a1ec-110">Ruft ab oder legt den Zielschlüssel.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-110">Gets or sets the target secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetUser">
      <MemberSignature Language="C#" Value="public string TargetUser { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.TargetUser" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetUser As String" />
      <MemberSignature Language="F#" Value="member this.TargetUser : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.TargetUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetUser")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a1ec-111">Ruft ab oder legt die CHAP Zielbenutzer.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-111">Gets or sets the CHAP target user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="chapSettings.Validate " />
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
            <span data-ttu-id="3a1ec-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3a1ec-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3a1ec-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3a1ec-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
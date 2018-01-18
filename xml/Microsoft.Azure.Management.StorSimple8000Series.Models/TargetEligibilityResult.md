<Type Name="TargetEligibilityResult" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult">
  <TypeSignature Language="C#" Value="public class TargetEligibilityResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TargetEligibilityResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Class TargetEligibilityResult" />
  <TypeSignature Language="F#" Value="type TargetEligibilityResult = class" />
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
            <span data-ttu-id="dde4b-101">Das Ergebnis der Berechtigung eines Geräts, als ein Failover-Zielgerät.</span><span class="sxs-lookup"><span data-stu-id="dde4b-101">The eligibility result of device, as a failover target device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TargetEligibilityResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dde4b-102">Initialisiert eine neue Instanz der TargetEligibilityResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dde4b-102">Initializes a new instance of the TargetEligibilityResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TargetEligibilityResult (Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; eligibilityStatus = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; messages = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; eligibilityStatus, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.#ctor(System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eligibilityStatus As Nullable(Of TargetEligibilityStatus) = null, Optional messages As IList(Of TargetEligibilityErrorMessage) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult (eligibilityStatus, messages)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eligibilityStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt;" />
        <Parameter Name="messages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="eligibilityStatus"><span data-ttu-id="dde4b-103">Der Status der Berechtigung eines Geräts, als ein Failover-Zielgerät.</span><span class="sxs-lookup"><span data-stu-id="dde4b-103">The eligibility status of device, as a failover target device.</span></span> <span data-ttu-id="dde4b-104">Folgende Werte sind möglich: "NotEligible", "Berechtigter"</span><span class="sxs-lookup"><span data-stu-id="dde4b-104">Possible values include: 'NotEligible', 'Eligible'</span></span></param>
        <param name="messages"><span data-ttu-id="dde4b-105">Die Liste der Fehlermeldungen, wenn ein Gerät nicht als Zielgerät Failover erfüllt.</span><span class="sxs-lookup"><span data-stu-id="dde4b-105">The list of error messages, if a device does not qualify as a failover target device.</span></span></param>
        <summary>
            <span data-ttu-id="dde4b-106">Initialisiert eine neue Instanz der TargetEligibilityResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dde4b-106">Initializes a new instance of the TargetEligibilityResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EligibilityStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; EligibilityStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; EligibilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.EligibilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EligibilityStatus As Nullable(Of TargetEligibilityStatus)" />
      <MemberSignature Language="F#" Value="member this.EligibilityStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.EligibilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eligibilityStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dde4b-107">Abrufen oder Festlegen der Berechtigung Status eines Geräts, als ein Failover-Zielgerät.</span><span class="sxs-lookup"><span data-stu-id="dde4b-107">Gets or sets the eligibility status of device, as a failover target device.</span></span> <span data-ttu-id="dde4b-108">Folgende Werte sind möglich: "NotEligible", "Berechtigter"</span><span class="sxs-lookup"><span data-stu-id="dde4b-108">Possible values include: 'NotEligible', 'Eligible'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Messages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; Messages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; Messages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.Messages" />
      <MemberSignature Language="VB.NET" Value="Public Property Messages As IList(Of TargetEligibilityErrorMessage)" />
      <MemberSignature Language="F#" Value="member this.Messages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.Messages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="messages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dde4b-109">Ruft ab oder legt die Liste der Fehlermeldungen, wenn ein Gerät nicht als Zielgerät Failover erfüllt.</span><span class="sxs-lookup"><span data-stu-id="dde4b-109">Gets or sets the list of error messages, if a device does not qualify as a failover target device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="InstanceViewStatus" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus">
  <TypeSignature Language="C#" Value="public class InstanceViewStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InstanceViewStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class InstanceViewStatus" />
  <TypeSignature Language="F#" Value="type InstanceViewStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="17c2b-101">Status der Instanz anzeigen.</span><span class="sxs-lookup"><span data-stu-id="17c2b-101">Instance view status.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InstanceViewStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="17c2b-102">Initialisiert eine neue Instanz der InstanceViewStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="17c2b-102">Initializes a new instance of the InstanceViewStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InstanceViewStatus (string code = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; level = null, string displayStatus = null, string message = null, Nullable&lt;DateTime&gt; time = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; level, string displayStatus, string message, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; time) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes},System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional level As Nullable(Of StatusLevelTypes) = null, Optional displayStatus As String = null, Optional message As String = null, Optional time As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus : string * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; * string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus (code, level, displayStatus, message, time)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt;" />
        <Parameter Name="displayStatus" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="time" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="17c2b-103">Der Statuscode.</span><span class="sxs-lookup"><span data-stu-id="17c2b-103">The status code.</span></span></param>
        <param name="level"><span data-ttu-id="17c2b-104">Der Code, Ebene.</span><span class="sxs-lookup"><span data-stu-id="17c2b-104">The level code.</span></span> <span data-ttu-id="17c2b-105">Folgende Werte sind möglich: "Info", "Warnung", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="17c2b-105">Possible values include: 'Info', 'Warning', 'Error'</span></span></param>
        <param name="displayStatus"><span data-ttu-id="17c2b-106">Die kurzen lokalisierbare Bezeichnung für den Status.</span><span class="sxs-lookup"><span data-stu-id="17c2b-106">The short localizable label for the status.</span></span></param>
        <param name="message"><span data-ttu-id="17c2b-107">Die detaillierte Statusmeldung, einschließlich Warnungen und Fehlermeldungen.</span><span class="sxs-lookup"><span data-stu-id="17c2b-107">The detailed status message, including for alerts and error messages.</span></span></param>
        <param name="time"><span data-ttu-id="17c2b-108">Die Zeit des Status.</span><span class="sxs-lookup"><span data-stu-id="17c2b-108">The time of the status.</span></span></param>
        <summary>
            <span data-ttu-id="17c2b-109">Initialisiert eine neue Instanz der InstanceViewStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="17c2b-109">Initializes a new instance of the InstanceViewStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17c2b-110">Ruft ab oder legt den Statuscode.</span><span class="sxs-lookup"><span data-stu-id="17c2b-110">Gets or sets the status code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayStatus">
      <MemberSignature Language="C#" Value="public string DisplayStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.DisplayStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayStatus As String" />
      <MemberSignature Language="F#" Value="member this.DisplayStatus : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.DisplayStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17c2b-111">Ermittelt oder definiert die kurze lokalisierbare Bezeichnung für den Status.</span><span class="sxs-lookup"><span data-stu-id="17c2b-111">Gets or sets the short localizable label for the status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of StatusLevelTypes)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17c2b-112">Abrufen oder festlegen den Ebenen Code.</span><span class="sxs-lookup"><span data-stu-id="17c2b-112">Gets or sets the level code.</span></span> <span data-ttu-id="17c2b-113">Folgende Werte sind möglich: "Info", "Warnung", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="17c2b-113">Possible values include: 'Info', 'Warning', 'Error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="17c2b-114">Ruft ab oder legt die detaillierte Statusmeldung, einschließlich Warnungen und Fehlermeldungen.</span><span class="sxs-lookup"><span data-stu-id="17c2b-114">Gets or sets the detailed status message, including for alerts and error messages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Time { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Time" />
      <MemberSignature Language="VB.NET" Value="Public Property Time As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Time : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17c2b-115">Ruft ab oder legt die Zeit des Status.</span><span class="sxs-lookup"><span data-stu-id="17c2b-115">Gets or sets the time of the status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
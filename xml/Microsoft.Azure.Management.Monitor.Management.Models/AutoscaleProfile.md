<Type Name="AutoscaleProfile" FullName="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile">
  <TypeSignature Language="C#" Value="public class AutoscaleProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoscaleProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoscaleProfile" />
  <TypeSignature Language="F#" Value="type AutoscaleProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bfdce-101">Autoskalierungsprofil.</span><span class="sxs-lookup"><span data-stu-id="bfdce-101">Autoscale profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bfdce-102">Initialisiert eine neue Instanz der AutoscaleProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bfdce-102">Initializes a new instance of the AutoscaleProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleProfile (string name, Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity capacity, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; rules, Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow fixedDate = null, Microsoft.Azure.Management.Monitor.Management.Models.Recurrence recurrence = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity capacity, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; rules, class Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow fixedDate, class Microsoft.Azure.Management.Monitor.Management.Models.Recurrence recurrence) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.#ctor(System.String,Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule},Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow,Microsoft.Azure.Management.Monitor.Management.Models.Recurrence)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile : string * Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; * Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow * Microsoft.Azure.Management.Monitor.Management.Models.Recurrence -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile (name, capacity, rules, fixedDate, recurrence)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity" />
        <Parameter Name="rules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt;" />
        <Parameter Name="fixedDate" Type="Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow" />
        <Parameter Name="recurrence" Type="Microsoft.Azure.Management.Monitor.Management.Models.Recurrence" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="bfdce-103">der Name des Profils.</span><span class="sxs-lookup"><span data-stu-id="bfdce-103">the name of the profile.</span></span></param>
        <param name="capacity"><span data-ttu-id="bfdce-104">Die Anzahl der Instanzen, die während dieses Profil verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="bfdce-104">the number of instances that can be used during this profile.</span></span></param>
        <param name="rules"><span data-ttu-id="bfdce-105">die Auflistung von Regeln, die den Trigger und die Parameter für die skalierungsaktion bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="bfdce-105">the collection of rules that provide the triggers and parameters for the scaling action.</span></span> <span data-ttu-id="bfdce-106">Es kann maximal 10 Regeln angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="bfdce-106">A maximum of 10 rules can be specified.</span></span></param>
        <param name="fixedDate"><span data-ttu-id="bfdce-107">bestimmtes Datum und Uhrzeit für das Profil.</span><span class="sxs-lookup"><span data-stu-id="bfdce-107">the specific date-time for the profile.</span></span>
            <span data-ttu-id="bfdce-108">Dieses Element wird nicht verwendet werden, wenn das Recurrence-Element verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="bfdce-108">This element is not used if the Recurrence element is used.</span></span></param>
        <param name="recurrence"><span data-ttu-id="bfdce-109">Die wiederholten Uhrzeiten, an denen dieses Profil beginnt.</span><span class="sxs-lookup"><span data-stu-id="bfdce-109">the repeating times at which this profile begins.</span></span> <span data-ttu-id="bfdce-110">Dieses Element wird nicht verwendet werden, wenn das FixedDate-Element verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="bfdce-110">This element is not used if the FixedDate element is used.</span></span></param>
        <summary>
            <span data-ttu-id="bfdce-111">Initialisiert eine neue Instanz der AutoscaleProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bfdce-111">Initializes a new instance of the AutoscaleProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As ScaleCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfdce-112">Ruft ab oder legt die Anzahl der Instanzen, die während dieses Profil verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="bfdce-112">Gets or sets the number of instances that can be used during this profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FixedDate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow FixedDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow FixedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.FixedDate" />
      <MemberSignature Language="VB.NET" Value="Public Property FixedDate As TimeWindow" />
      <MemberSignature Language="F#" Value="member this.FixedDate : Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.FixedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fixedDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfdce-113">Ruft ab oder legt bestimmte Datum und Uhrzeit für das Profil.</span><span class="sxs-lookup"><span data-stu-id="bfdce-113">Gets or sets the specific date-time for the profile.</span></span> <span data-ttu-id="bfdce-114">Dieses Element wird nicht verwendet werden, wenn das Recurrence-Element verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="bfdce-114">This element is not used if the Recurrence element is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfdce-115">Ruft ab oder legt den Namen des Profils.</span><span class="sxs-lookup"><span data-stu-id="bfdce-115">Gets or sets the name of the profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recurrence">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.Recurrence Recurrence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.Recurrence Recurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Recurrence" />
      <MemberSignature Language="VB.NET" Value="Public Property Recurrence As Recurrence" />
      <MemberSignature Language="F#" Value="member this.Recurrence : Microsoft.Azure.Management.Monitor.Management.Models.Recurrence with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Recurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrence")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.Recurrence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfdce-116">Ruft ab oder legt die wiederholten Zeitpunkten, an denen dieses Profil beginnt.</span><span class="sxs-lookup"><span data-stu-id="bfdce-116">Gets or sets the repeating times at which this profile begins.</span></span> <span data-ttu-id="bfdce-117">Dieses Element wird nicht verwendet werden, wenn das FixedDate-Element verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="bfdce-117">This element is not used if the FixedDate element is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; Rules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; Rules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Rules" />
      <MemberSignature Language="VB.NET" Value="Public Property Rules As IList(Of ScaleRule)" />
      <MemberSignature Language="F#" Value="member this.Rules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Rules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfdce-118">Ruft ab oder legt die Auflistung der Regeln, die den Trigger und die Parameter für die skalierungsaktion bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="bfdce-118">Gets or sets the collection of rules that provide the triggers and parameters for the scaling action.</span></span> <span data-ttu-id="bfdce-119">Es kann maximal 10 Regeln angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="bfdce-119">A maximum of 10 rules can be specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoscaleProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bfdce-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="bfdce-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bfdce-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="bfdce-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
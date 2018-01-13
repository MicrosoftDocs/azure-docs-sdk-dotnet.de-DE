<Type Name="ActivityLogAlertAllOfCondition" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition">
  <TypeSignature Language="C#" Value="public class ActivityLogAlertAllOfCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityLogAlertAllOfCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityLogAlertAllOfCondition" />
  <TypeSignature Language="F#" Value="type ActivityLogAlertAllOfCondition = class" />
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
            <span data-ttu-id="a2e1e-101">Eine warnungsbedingung Aktivitätsprotokoll erfüllt wird, wenn alle seine Member Bedingungen erfüllt sind.</span><span class="sxs-lookup"><span data-stu-id="a2e1e-101">An Activity Log alert condition that is met when all its member conditions are met.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertAllOfCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition.#ctor" />
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
            <span data-ttu-id="a2e1e-102">Initialisiert eine neue Instanz der ActivityLogAlertAllOfCondition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a2e1e-102">Initializes a new instance of the ActivityLogAlertAllOfCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertAllOfCondition (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition&gt; allOf);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition&gt; allOf) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (allOf As IList(Of ActivityLogAlertLeafCondition))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition allOf" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="allOf" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition&gt;" />
      </Parameters>
      <Docs>
        <param name="allOf"><span data-ttu-id="a2e1e-103">Die Liste der Protokoll-warnungsbedingungen Aktivität.</span><span class="sxs-lookup"><span data-stu-id="a2e1e-103">The list of activity log alert conditions.</span></span></param>
        <summary>
            <span data-ttu-id="a2e1e-104">Initialisiert eine neue Instanz der ActivityLogAlertAllOfCondition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a2e1e-104">Initializes a new instance of the ActivityLogAlertAllOfCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllOf">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition&gt; AllOf { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition&gt; AllOf" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition.AllOf" />
      <MemberSignature Language="VB.NET" Value="Public Property AllOf As IList(Of ActivityLogAlertLeafCondition)" />
      <MemberSignature Language="F#" Value="member this.AllOf : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition.AllOf" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allOf")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e1e-105">Ruft ab oder legt die Liste der Aktivität warnungsbedingungen Protokoll.</span><span class="sxs-lookup"><span data-stu-id="a2e1e-105">Gets or sets the list of activity log alert conditions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertAllOfCondition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="activityLogAlertAllOfCondition.Validate " />
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
            <span data-ttu-id="a2e1e-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a2e1e-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a2e1e-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a2e1e-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ComputePolicyCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class ComputePolicyCreateOrUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputePolicyCreateOrUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputePolicyCreateOrUpdateParameters" />
  <TypeSignature Language="F#" Value="type ComputePolicyCreateOrUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Parameter zum Erstellen einer neuen Compute-Richtlinie verwendet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputePolicyCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ComputePolicyCreateOrUpdateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputePolicyCreateOrUpdateParameters (Guid objectId, string objectType, Nullable&lt;int&gt; maxDegreeOfParallelismPerJob = null, Nullable&lt;int&gt; minPriorityPerJob = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid objectId, string objectType, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelismPerJob, valuetype System.Nullable`1&lt;int32&gt; minPriorityPerJob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.#ctor(System.Guid,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (objectId As Guid, objectType As String, Optional maxDegreeOfParallelismPerJob As Nullable(Of Integer) = null, Optional minPriorityPerJob As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters : Guid * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters (objectId, objectType, maxDegreeOfParallelismPerJob, minPriorityPerJob)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="objectId" Type="System.Guid" />
        <Parameter Name="objectType" Type="System.String" />
        <Parameter Name="maxDegreeOfParallelismPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minPriorityPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="objectId">Die AAD-Objekt-ID für die Entität, die eine Richtlinie erstellen.</param>
        <param name="objectType">Der Typ des Objekts für AAD bezieht sich die Objekt-ID auf. Folgende Werte sind möglich: "User", "Group", "ServicePrincipal"</param>
        <param name="maxDegreeOfParallelismPerJob">Diese Benutzer können den maximalen Grad an Parallelität pro Auftrag Übermitteln von Aufträgen. Diese Eigenschaft muss die Priorität Min. pro Auftrag-Eigenschaft oder sowohl übergeben werden.</param>
        <param name="minPriorityPerJob">Der minimalen Priorität pro Auftrag kann dieser Benutzer zum Übermitteln von Aufträgen verwenden. Diese Eigenschaft muss der Max. Grad an Parallelität pro Auftrag-Eigenschaft oder sowohl übergeben werden.</param>
        <summary>
            Initialisiert eine neue Instanz der ComputePolicyCreateOrUpdateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelismPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelismPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelismPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelismPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.MaxDegreeOfParallelismPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDegreeOfParallelismPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den maximalen Grad an Parallelität pro Auftrag, den dieser Benutzer zum Übermitteln von Aufträgen verwenden kann. Diese Eigenschaft muss die Priorität Min. pro Auftrag-Eigenschaft oder sowohl übergeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinPriorityPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinPriorityPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinPriorityPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.MinPriorityPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MinPriorityPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinPriorityPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.MinPriorityPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minPriorityPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die minimale Priorität pro Auftrag, den dieser Benutzer zum Übermitteln von Aufträgen verwenden kann. Diese Eigenschaft muss der Max. Grad an Parallelität pro Auftrag-Eigenschaft oder sowohl übergeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public Guid ObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectId As Guid" />
      <MemberSignature Language="F#" Value="member this.ObjectId : Guid with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.objectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der AAD-Objekt-ID für die Entität, die eine Richtlinie erstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectType">
      <MemberSignature Language="C#" Value="public string ObjectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.ObjectType" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectType As String" />
      <MemberSignature Language="F#" Value="member this.ObjectType : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.ObjectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.objectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des AAD-Objekts, auf die die Objekt-ID verweist. Folgende Werte sind möglich: "User", "Group", "ServicePrincipal"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computePolicyCreateOrUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
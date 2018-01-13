<Type Name="BuildJobParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters">
  <TypeSignature Language="C#" Value="public class BuildJobParameters : Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BuildJobParameters extends Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class BuildJobParameters&#xA;Inherits BaseJobParameters" />
  <TypeSignature Language="F#" Value="type BuildJobParameters = class&#xA;    inherit BaseJobParameters" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Parameter verwendet, um einen neuen Data Lake Analytics-Auftrag zu erstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BuildJobParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BuildJobParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BuildJobParameters (Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.#ctor(Microsoft.Azure.Management.DataLake.Analytics.Models.JobType,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As JobType, properties As CreateJobProperties, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters : Microsoft.Azure.Management.DataLake.Analytics.Models.JobType * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters (type, properties, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobType" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="type">Der Auftragstyp des aktuellen Auftrags (Hive oder USql).
            Folgende Werte sind möglich: "USql", "Struktur"</param>
        <param name="properties">die spezifischen Eigenschaften des Auftrags.</param>
        <param name="name">der angezeigte Name des Auftrags, zu erstellen.</param>
        <summary>
            Initialisiert eine neue Instanz der BuildJobParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Anzeigenamen des Auftrags, zu erstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="buildJobParameters.Validate " />
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
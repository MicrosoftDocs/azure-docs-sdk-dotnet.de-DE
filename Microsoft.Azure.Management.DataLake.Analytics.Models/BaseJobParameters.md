<Type Name="BaseJobParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters">
  <TypeSignature Language="C#" Value="public class BaseJobParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BaseJobParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class BaseJobParameters" />
  <TypeSignature Language="F#" Value="type BaseJobParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Data Lake Analytics-Auftrag-Parameter die Basisklasse für Build und übermitteln.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaseJobParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BaseJobParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaseJobParameters (Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters.#ctor(Microsoft.Azure.Management.DataLake.Analytics.Models.JobType,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As JobType, properties As CreateJobProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters : Microsoft.Azure.Management.DataLake.Analytics.Models.JobType * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters (type, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobType" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties" />
      </Parameters>
      <Docs>
        <param name="type">Der Auftragstyp des aktuellen Auftrags (Hive oder USql).
            Folgende Werte sind möglich: "USql", "Struktur"</param>
        <param name="properties">die spezifischen Eigenschaften des Auftrags.</param>
        <summary>
            Initialisiert eine neue Instanz der BaseJobParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As CreateJobProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Auftrags spezifische Eigenschaften.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As JobType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.DataLake.Analytics.Models.JobType with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Auftragstyp des aktuellen Auftrags (Hive oder USql).
            Folgende Werte sind möglich: "USql", "Struktur"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="baseJobParameters.Validate " />
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
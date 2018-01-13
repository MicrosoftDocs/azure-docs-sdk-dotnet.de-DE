<Type Name="OperationMetricSpecification" FullName="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification">
  <TypeSignature Language="C#" Value="public class OperationMetricSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationMetricSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationMetricSpecification" />
  <TypeSignature Language="F#" Value="type OperationMetricSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Details zu einem Vorgang im Zusammenhang mit Metriken.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationMetricSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der OperationMetricSpecification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationMetricSpecification (string name = null, string displayName = null, string displayDescription = null, string unit = null, string aggregationType = null, string enableRegionalMdmAccount = null, string sourceMdmAccount = null, string sourceMdmNamespace = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; availabilities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string displayDescription, string unit, string aggregationType, string enableRegionalMdmAccount, string sourceMdmAccount, string sourceMdmNamespace, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; availabilities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional displayDescription As String = null, Optional unit As String = null, Optional aggregationType As String = null, Optional enableRegionalMdmAccount As String = null, Optional sourceMdmAccount As String = null, Optional sourceMdmNamespace As String = null, Optional availabilities As IList(Of OperationMetricAvailability) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification : string * string * string * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification" Usage="new Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification (name, displayName, displayDescription, unit, aggregationType, enableRegionalMdmAccount, sourceMdmAccount, sourceMdmNamespace, availabilities)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="displayDescription" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="aggregationType" Type="System.String" />
        <Parameter Name="enableRegionalMdmAccount" Type="System.String" />
        <Parameter Name="sourceMdmAccount" Type="System.String" />
        <Parameter Name="sourceMdmNamespace" Type="System.String" />
        <Parameter Name="availabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Metrik.</param>
        <param name="displayName">Lokalisierten Anzeigenamen der Metrik.</param>
        <param name="displayDescription">Die Beschreibung der Metrik.</param>
        <param name="unit">Die Einheit, der die Metrik in gemessen wird.</param>
        <param name="aggregationType">Der Typ der Metrik Aggregation.</param>
        <param name="enableRegionalMdmAccount">Und zwar unabhängig davon, ob der Dienst regionale MDM-Konten verwendet.</param>
        <param name="sourceMdmAccount">Der Name des Kontos MDM.</param>
        <param name="sourceMdmNamespace">Der Name des MDM-Namespace.</param>
        <param name="availabilities">Definiert, wie oft die Daten für Metriken sind verfügbar.</param>
        <summary>
            Initialisiert eine neue Instanz der OperationMetricSpecification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregationType">
      <MemberSignature Language="C#" Value="public string AggregationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.AggregationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AggregationType As String" />
      <MemberSignature Language="F#" Value="member this.AggregationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.AggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Metrik Aggregation.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Availabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; Availabilities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; Availabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Availabilities" />
      <MemberSignature Language="VB.NET" Value="Public Property Availabilities As IList(Of OperationMetricAvailability)" />
      <MemberSignature Language="F#" Value="member this.Availabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Availabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest definiert, wie oft die Daten für Metriken sind verfügbar.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayDescription">
      <MemberSignature Language="C#" Value="public string DisplayDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.DisplayDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayDescription As String" />
      <MemberSignature Language="F#" Value="member this.DisplayDescription : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.DisplayDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Beschreibung der Metrik.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest lokalisierten Anzeigenamen der Metrik.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableRegionalMdmAccount">
      <MemberSignature Language="C#" Value="public string EnableRegionalMdmAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnableRegionalMdmAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.EnableRegionalMdmAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableRegionalMdmAccount As String" />
      <MemberSignature Language="F#" Value="member this.EnableRegionalMdmAccount : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.EnableRegionalMdmAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableRegionalMdmAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, und zwar unabhängig davon, ob der Dienst regionale MDM-Konten verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Namen der Metrik.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceMdmAccount">
      <MemberSignature Language="C#" Value="public string SourceMdmAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceMdmAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.SourceMdmAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceMdmAccount As String" />
      <MemberSignature Language="F#" Value="member this.SourceMdmAccount : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.SourceMdmAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceMdmAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Kontos MDM fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceMdmNamespace">
      <MemberSignature Language="C#" Value="public string SourceMdmNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceMdmNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.SourceMdmNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceMdmNamespace As String" />
      <MemberSignature Language="F#" Value="member this.SourceMdmNamespace : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.SourceMdmNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceMdmNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des MDM-Namespace.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Einheit, der die Metrik in gemessen wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
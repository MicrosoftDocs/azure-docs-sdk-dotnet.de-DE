<Type Name="Diagnostics" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics">
  <TypeSignature Language="C#" Value="public class Diagnostics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Diagnostics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" />
  <TypeSignature Language="VB.NET" Value="Public Class Diagnostics" />
  <TypeSignature Language="F#" Value="type Diagnostics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt die Bedingungen für die Eingabe, Ausgabe oder des Auftrags insgesamt, die Kunden ein Eingreifen erforderlich machen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Diagnostics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Diagnose-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Diagnostics (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; conditions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; conditions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional conditions As IList(Of DiagnosticCondition) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics conditions" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="conditions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt;" />
      </Parameters>
      <Docs>
        <param name="conditions">Eine Auflistung von NULL oder mehr Bedingungen zutreffend, auf die Ressource oder des Auftrags insgesamt, die Kunden ein Eingreifen erforderlich machen.</param>
        <summary>
            Initialisiert eine neue Instanz der Diagnose-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Conditions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; Conditions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; Conditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics.Conditions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Conditions As IList(Of DiagnosticCondition)" />
      <MemberSignature Language="F#" Value="member this.Conditions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics.Conditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="conditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Auflistung von NULL oder mehr Bedingungen zutreffend, auf die Ressource oder des Auftrags insgesamt, die Kunden Ihre Aufmerksamkeit erfordern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
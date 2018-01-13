<Type Name="RuleCondition" FullName="Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition">
  <TypeSignature Language="C#" Value="public class RuleCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RuleCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class RuleCondition" />
  <TypeSignature Language="F#" Value="type RuleCondition = class" />
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
            die Bedingung, die in der Benachrichtigungsregel aktiviert wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition.#ctor" />
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
            Initialisiert eine neue Instanz der RuleCondition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleCondition (Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dataSource As RuleDataSource = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition : Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource -&gt; Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition dataSource" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataSource" Type="Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource" />
      </Parameters>
      <Docs>
        <param name="dataSource">Die Ressource, von der die Regel erfasst die zugehörigen Daten. Für diesen Typ wird immer die Datenquelle des Typs RuleMetricDataSource sein.</param>
        <summary>
            Initialisiert eine neue Instanz der RuleCondition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource DataSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource DataSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition.DataSource" />
      <MemberSignature Language="VB.NET" Value="Public Property DataSource As RuleDataSource" />
      <MemberSignature Language="F#" Value="member this.DataSource : Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition.DataSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataSource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ressource, von der die Regel erfasst die zugehörigen Daten.
            Für diesen Typ wird immer die Datenquelle des Typs RuleMetricDataSource sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
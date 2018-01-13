<Type Name="LocationThresholdRuleCondition" FullName="Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition">
  <TypeSignature Language="C#" Value="public class LocationThresholdRuleCondition : Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LocationThresholdRuleCondition extends Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class LocationThresholdRuleCondition&#xA;Inherits RuleCondition" />
  <TypeSignature Language="F#" Value="type LocationThresholdRuleCondition = class&#xA;    inherit RuleCondition" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Azure.Management.Insights.Models.LocationThresholdRuleCondition")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine regelbedingung basierend auf einer bestimmten Anzahl von Standorten fehlschlagen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocationThresholdRuleCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.#ctor" />
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
            Initialisiert eine neue Instanz der LocationThresholdRuleCondition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocationThresholdRuleCondition (int failedLocationCount, Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource = null, Nullable&lt;TimeSpan&gt; windowSize = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 failedLocationCount, class Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; windowSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.#ctor(System.Int32,Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (failedLocationCount As Integer, Optional dataSource As RuleDataSource = null, Optional windowSize As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition : int * Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition (failedLocationCount, dataSource, windowSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="failedLocationCount" Type="System.Int32" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource" />
        <Parameter Name="windowSize" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="failedLocationCount">die Anzahl der Standorte, die ausfallen müssen, um die Warnung zu aktivieren.</param>
        <param name="dataSource">Die Ressource, von der die Regel erfasst die zugehörigen Daten. Für diesen Typ wird immer die Datenquelle des Typs RuleMetricDataSource sein.</param>
        <param name="windowSize">die Zeitspanne (in Dauer ISO 8601-Format), die verwendet wird, auf Grundlage des Schwellenwerts Aktivität zu überwachen. Wenn angegeben, muss zwischen 5 Minuten und 1 Tag sein.</param>
        <summary>
            Initialisiert eine neue Instanz der LocationThresholdRuleCondition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedLocationCount">
      <MemberSignature Language="C#" Value="public int FailedLocationCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FailedLocationCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.FailedLocationCount" />
      <MemberSignature Language="VB.NET" Value="Public Property FailedLocationCount As Integer" />
      <MemberSignature Language="F#" Value="member this.FailedLocationCount : int with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.FailedLocationCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failedLocationCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Standorte, die ausfallen müssen, um die Warnung zu aktivieren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="locationThresholdRuleCondition.Validate " />
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WindowSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; WindowSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; WindowSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.WindowSize" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowSize As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.WindowSize : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.WindowSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeitspanne (in Dauer ISO 8601-Format) an, die verwendet wird, auf Grundlage des Schwellenwerts Aktivität zu überwachen. Wenn angegeben, muss zwischen 5 Minuten und 1 Tag sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
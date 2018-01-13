<Type Name="WindowsConfiguration" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration">
  <TypeSignature Language="C#" Value="public class WindowsConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsConfiguration" />
  <TypeSignature Language="F#" Value="type WindowsConfiguration = class" />
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
            Beschreibt die Windows-Konfiguration des Profils OS.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der WindowsConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsConfiguration (Nullable&lt;bool&gt; provisionVMAgent = null, Nullable&lt;bool&gt; enableAutomaticUpdates = null, string timeZone = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent&gt; additionalUnattendContent = null, Microsoft.Azure.Management.Compute.Fluent.Models.WinRMConfiguration winRM = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; provisionVMAgent, valuetype System.Nullable`1&lt;bool&gt; enableAutomaticUpdates, string timeZone, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent&gt; additionalUnattendContent, class Microsoft.Azure.Management.Compute.Fluent.Models.WinRMConfiguration winRM) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.#ctor(System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent},Microsoft.Azure.Management.Compute.Fluent.Models.WinRMConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provisionVMAgent As Nullable(Of Boolean) = null, Optional enableAutomaticUpdates As Nullable(Of Boolean) = null, Optional timeZone As String = null, Optional additionalUnattendContent As IList(Of AdditionalUnattendContent) = null, Optional winRM As WinRMConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration : Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.WinRMConfiguration -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration (provisionVMAgent, enableAutomaticUpdates, timeZone, additionalUnattendContent, winRM)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provisionVMAgent" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableAutomaticUpdates" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="timeZone" Type="System.String" />
        <Parameter Name="additionalUnattendContent" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent&gt;" />
        <Parameter Name="winRM" Type="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMConfiguration" />
      </Parameters>
      <Docs>
        <param name="provisionVMAgent">Gibt an, ob der VM-Agent auf dem virtuellen Computer bereitgestellt werden soll. Wenn nicht angegeben wird, ist das Standardverhalten auf "true" festlegen.</param>
        <param name="enableAutomaticUpdates">Gibt an, ob Windows-Updates automatisch auf dem virtuellen Computer installiert sind.</param>
        <param name="timeZone">Die Zeitzone des virtuellen Computers</param>
        <param name="additionalUnattendContent">Zusätzliches Base64-codiertes XML formatiert Informationen, die in der Datei "Unattend.xml" aufgenommen werden kann.</param>
        <param name="winRM">Die Windows-Remoteverwaltung-Konfiguration des virtuellen Computers</param>
        <summary>
            Initialisiert eine neue Instanz der WindowsConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalUnattendContent">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent&gt; AdditionalUnattendContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent&gt; AdditionalUnattendContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.AdditionalUnattendContent" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalUnattendContent As IList(Of AdditionalUnattendContent)" />
      <MemberSignature Language="F#" Value="member this.AdditionalUnattendContent : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.AdditionalUnattendContent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="additionalUnattendContent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert zusätzliche Base-64-codierte XML-Format Informationen, die in der Datei "Unattend.xml" aufgenommen werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutomaticUpdates">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAutomaticUpdates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAutomaticUpdates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.EnableAutomaticUpdates" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAutomaticUpdates As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAutomaticUpdates : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.EnableAutomaticUpdates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableAutomaticUpdates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob es sich bei Windows-Updates automatisch auf dem virtuellen Computer installiert sind, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionVMAgent">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ProvisionVMAgent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ProvisionVMAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.ProvisionVMAgent" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionVMAgent As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ProvisionVMAgent : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.ProvisionVMAgent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisionVMAgent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, ob der VM-Agent auf dem virtuellen Computer bereitgestellt werden soll. Wenn nicht angegeben wird, ist das Standardverhalten auf "true" festlegen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeitzone des virtuellen Computers
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WinRM">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.WinRMConfiguration WinRM { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.WinRMConfiguration WinRM" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.WinRM" />
      <MemberSignature Language="VB.NET" Value="Public Property WinRM As WinRMConfiguration" />
      <MemberSignature Language="F#" Value="member this.WinRM : Microsoft.Azure.Management.Compute.Fluent.Models.WinRMConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration.WinRM" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="winRM")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.WinRMConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Windows-Remoteverwaltung-Konfiguration des virtuellen Computers fest
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
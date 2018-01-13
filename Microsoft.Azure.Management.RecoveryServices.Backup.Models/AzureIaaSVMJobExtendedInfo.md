<Type Name="AzureIaaSVMJobExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo">
  <TypeSignature Language="C#" Value="public class AzureIaaSVMJobExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSVMJobExtendedInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSVMJobExtendedInfo" />
  <TypeSignature Language="F#" Value="type AzureIaaSVMJobExtendedInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure IaaS-VM spezifische zusätzliche Informationen für Auftragsschritte.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMJobExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureIaaSVMJobExtendedInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMJobExtendedInfo (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobTaskDetails&gt; tasksList = null, System.Collections.Generic.IDictionary&lt;string,string&gt; propertyBag = null, Nullable&lt;double&gt; progressPercentage = null, string dynamicErrorMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobTaskDetails&gt; tasksList, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; propertyBag, valuetype System.Nullable`1&lt;float64&gt; progressPercentage, string dynamicErrorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobTaskDetails},System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Double},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tasksList As IList(Of AzureIaaSVMJobTaskDetails) = null, Optional propertyBag As IDictionary(Of String, String) = null, Optional progressPercentage As Nullable(Of Double) = null, Optional dynamicErrorMessage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobTaskDetails&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;double&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo (tasksList, propertyBag, progressPercentage, dynamicErrorMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tasksList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobTaskDetails&gt;" />
        <Parameter Name="propertyBag" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="progressPercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="dynamicErrorMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tasksList">Liste der Aufgaben im Zusammenhang mit diesem Auftrag.</param>
        <param name="propertyBag">Auftragseigenschaften.</param>
        <param name="progressPercentage">Gibt Status des Auftrags an.
            NULL, wenn er nicht gestartet oder abgeschlossen wurde.</param>
        <param name="dynamicErrorMessage">Nicht lokalisierte Fehlermeldung bei der auftragsausführung.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureIaaSVMJobExtendedInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicErrorMessage">
      <MemberSignature Language="C#" Value="public string DynamicErrorMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DynamicErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.DynamicErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.DynamicErrorMessage : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.DynamicErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dynamicErrorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt für nicht lokalisierte Fehlermeldung bei der auftragsausführung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProgressPercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ProgressPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ProgressPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.ProgressPercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property ProgressPercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ProgressPercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.ProgressPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="progressPercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt Fortschritt des Auftrags an. NULL, wenn er nicht gestartet oder abgeschlossen wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyBag">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; PropertyBag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; PropertyBag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.PropertyBag" />
      <MemberSignature Language="VB.NET" Value="Public Property PropertyBag As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.PropertyBag : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.PropertyBag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="propertyBag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt die Auftragseigenschaften fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TasksList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobTaskDetails&gt; TasksList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobTaskDetails&gt; TasksList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.TasksList" />
      <MemberSignature Language="VB.NET" Value="Public Property TasksList As IList(Of AzureIaaSVMJobTaskDetails)" />
      <MemberSignature Language="F#" Value="member this.TasksList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobTaskDetails&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo.TasksList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tasksList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobTaskDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Aufgaben im Zusammenhang mit diesem Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
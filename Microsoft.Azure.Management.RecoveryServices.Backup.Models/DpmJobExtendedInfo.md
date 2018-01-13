<Type Name="DpmJobExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo">
  <TypeSignature Language="C#" Value="public class DpmJobExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DpmJobExtendedInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class DpmJobExtendedInfo" />
  <TypeSignature Language="F#" Value="type DpmJobExtendedInfo = class" />
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
            <span data-ttu-id="cc079-101">Weitere Informationen zu DPM-spezifische Auftrag.</span><span class="sxs-lookup"><span data-stu-id="cc079-101">Additional information on the DPM workload-specific job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmJobExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cc079-102">Initialisiert eine neue Instanz der DpmJobExtendedInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cc079-102">Initializes a new instance of the DpmJobExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmJobExtendedInfo (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails&gt; tasksList = null, System.Collections.Generic.IDictionary&lt;string,string&gt; propertyBag = null, string dynamicErrorMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails&gt; tasksList, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; propertyBag, string dynamicErrorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails},System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tasksList As IList(Of DpmJobTaskDetails) = null, Optional propertyBag As IDictionary(Of String, String) = null, Optional dynamicErrorMessage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo (tasksList, propertyBag, dynamicErrorMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tasksList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails&gt;" />
        <Parameter Name="propertyBag" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="dynamicErrorMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tasksList"><span data-ttu-id="cc079-103">Liste der Aufgaben im Zusammenhang mit diesem Auftrag.</span><span class="sxs-lookup"><span data-stu-id="cc079-103">List of tasks associated with this job.</span></span></param>
        <param name="propertyBag"><span data-ttu-id="cc079-104">Die Auftragseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="cc079-104">The job properties.</span></span></param>
        <param name="dynamicErrorMessage"><span data-ttu-id="cc079-105">Nicht lokalisierte Fehlermeldung bei der auftragsausführung.</span><span class="sxs-lookup"><span data-stu-id="cc079-105">Non localized error message on job execution.</span></span></param>
        <summary>
            <span data-ttu-id="cc079-106">Initialisiert eine neue Instanz der DpmJobExtendedInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cc079-106">Initializes a new instance of the DpmJobExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicErrorMessage">
      <MemberSignature Language="C#" Value="public string DynamicErrorMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DynamicErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo.DynamicErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.DynamicErrorMessage : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo.DynamicErrorMessage" />
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
            <span data-ttu-id="cc079-107">Ruft ab oder legt für nicht lokalisierte Fehlermeldung bei der auftragsausführung.</span><span class="sxs-lookup"><span data-stu-id="cc079-107">Gets or sets non localized error message on job execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyBag">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; PropertyBag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; PropertyBag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo.PropertyBag" />
      <MemberSignature Language="VB.NET" Value="Public Property PropertyBag As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.PropertyBag : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo.PropertyBag" />
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
            <span data-ttu-id="cc079-108">Ruft ab oder legt die Auftragseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="cc079-108">Gets or sets the job properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TasksList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails&gt; TasksList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails&gt; TasksList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo.TasksList" />
      <MemberSignature Language="VB.NET" Value="Public Property TasksList As IList(Of DpmJobTaskDetails)" />
      <MemberSignature Language="F#" Value="member this.TasksList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo.TasksList" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc079-109">Ruft ab oder legt die Liste der Aufgaben im Zusammenhang mit diesem Auftrag.</span><span class="sxs-lookup"><span data-stu-id="cc079-109">Gets or sets list of tasks associated with this job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
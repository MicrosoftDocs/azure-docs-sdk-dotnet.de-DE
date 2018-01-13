<Type Name="JobSchedulePatchParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter">
  <TypeSignature Language="C#" Value="public class JobSchedulePatchParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobSchedulePatchParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSchedulePatchParameter" />
  <TypeSignature Language="F#" Value="type JobSchedulePatchParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Satz von Änderungen an den Zeitplan für einen Auftrag vorgenommen werden müssen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSchedulePatchParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobSchedulePatchParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSchedulePatchParameter (Microsoft.Azure.Batch.Protocol.Models.Schedule schedule = null, Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.Schedule schedule, class Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.#ctor(Microsoft.Azure.Batch.Protocol.Models.Schedule,Microsoft.Azure.Batch.Protocol.Models.JobSpecification,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter : Microsoft.Azure.Batch.Protocol.Models.Schedule * Microsoft.Azure.Batch.Protocol.Models.JobSpecification * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter (schedule, jobSpecification, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schedule" Type="Microsoft.Azure.Batch.Protocol.Models.Schedule" />
        <Parameter Name="jobSpecification" Type="Microsoft.Azure.Batch.Protocol.Models.JobSpecification" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="schedule">Der Zeitplan entsprechend, den Aufträge erstellt werden soll.</param>
        <param name="jobSpecification">Die Details der Aufträge, die auf diesen Zeitplan erstellt werden.</param>
        <param name="metadata">Eine Liste von Name / Wert-Paaren, die den Auftragszeitplan als Metadaten zugeordnet.</param>
        <summary>
            Initialisiert eine neue Instanz der JobSchedulePatchParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.JobSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property JobSpecification As JobSpecification" />
      <MemberSignature Language="F#" Value="member this.JobSpecification : Microsoft.Azure.Batch.Protocol.Models.JobSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.JobSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobSpecification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Details der Aufträge, die auf diesen Zeitplan erstellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Updates betreffen nur die Aufträge, die gestartet werden, nachdem das Update stattgefunden hat. Alle derzeit aktiven Auftrag wird mit der älteren Spezifikation fortgesetzt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Name / Wert-Paaren, die den Auftragszeitplan als Metadaten zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn Sie keinen dieses Element angeben vorhandenen Metadaten unverändert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As Schedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Batch.Protocol.Models.Schedule with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.Schedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitplan, nach dem Aufträge erstellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn Sie dieses Element nicht angeben, der Zeitplan des vorhandene bleibt unverändert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobSchedulePatchParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
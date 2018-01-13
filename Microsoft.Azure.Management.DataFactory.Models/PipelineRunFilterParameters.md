<Type Name="PipelineRunFilterParameters" FullName="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters">
  <TypeSignature Language="C#" Value="public class PipelineRunFilterParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineRunFilterParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineRunFilterParameters" />
  <TypeSignature Language="F#" Value="type PipelineRunFilterParameters = class" />
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
            Der Abfrageparameter für das Auflisten von Pipeline ausgeführt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunFilterParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.#ctor" />
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
            Initialisiert eine neue Instanz der PipelineRunFilterParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunFilterParameters (DateTime lastUpdatedAfter, DateTime lastUpdatedBefore, string continuationToken = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter&gt; filters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy&gt; orderBy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime lastUpdatedAfter, valuetype System.DateTime lastUpdatedBefore, string continuationToken, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter&gt; filters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy&gt; orderBy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.#ctor(System.DateTime,System.DateTime,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lastUpdatedAfter As DateTime, lastUpdatedBefore As DateTime, Optional continuationToken As String = null, Optional filters As IList(Of PipelineRunQueryFilter) = null, Optional orderBy As IList(Of PipelineRunQueryOrderBy) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters : DateTime * DateTime * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters" Usage="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters (lastUpdatedAfter, lastUpdatedBefore, continuationToken, filters, orderBy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lastUpdatedAfter" Type="System.DateTime" />
        <Parameter Name="lastUpdatedBefore" Type="System.DateTime" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="filters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter&gt;" />
        <Parameter Name="orderBy" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy&gt;" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedAfter">Formatieren Sie die Zeit, die am oder nach dem die Pipeline ausgeführt-Ereignis in "ISO 8601" aktualisiert wurde.</param>
        <param name="lastUpdatedBefore">Formatieren Sie die Zeit, die am oder vor dem das Ereignis Pipeline ausführen in "ISO 8601" aktualisiert wurde.</param>
        <param name="continuationToken">Das Fortsetzungstoken zum Abrufen der nächsten Seite mit Ergebnissen. NULL für die erste Seite.</param>
        <param name="filters">Liste der Filter.</param>
        <param name="orderBy">Liste der OrderBy-Option.</param>
        <summary>
            Initialisiert eine neue Instanz der PipelineRunFilterParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="continuationToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Fortsetzungstoken zum Abrufen der nächsten Seite mit Ergebnissen. NULL für die erste Seite.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter&gt; Filters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter&gt; Filters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.Filters" />
      <MemberSignature Language="VB.NET" Value="Public Property Filters As IList(Of PipelineRunQueryFilter)" />
      <MemberSignature Language="F#" Value="member this.Filters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.Filters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Filter.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdatedAfter">
      <MemberSignature Language="C#" Value="public DateTime LastUpdatedAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdatedAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.LastUpdatedAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdatedAfter As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdatedAfter : DateTime with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.LastUpdatedAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdatedAfter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit fest, um oder nach dem die Pipeline Ereignis ausführen im Format "ISO 8601" aktualisiert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdatedBefore">
      <MemberSignature Language="C#" Value="public DateTime LastUpdatedBefore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdatedBefore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.LastUpdatedBefore" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdatedBefore As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdatedBefore : DateTime with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.LastUpdatedBefore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdatedBefore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit fest, an oder vor dem die Pipeline Ereignis ausführen im Format "ISO 8601" aktualisiert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy&gt; OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy&gt; OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As IList(Of PipelineRunQueryOrderBy)" />
      <MemberSignature Language="F#" Value="member this.OrderBy : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.OrderBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="orderBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der OrderBy-Option.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pipelineRunFilterParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
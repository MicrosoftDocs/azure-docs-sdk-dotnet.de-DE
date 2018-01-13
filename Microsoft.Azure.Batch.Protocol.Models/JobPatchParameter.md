<Type Name="JobPatchParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter">
  <TypeSignature Language="C#" Value="public class JobPatchParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPatchParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPatchParameter" />
  <TypeSignature Language="F#" Value="type JobPatchParameter = class" />
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
            Der Satz von Änderungen an einen Auftrag vorgenommen werden müssen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPatchParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.#ctor" />
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
            Initialisiert eine neue Instanz der JobPatchParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPatchParameter (Nullable&lt;int&gt; priority = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; priority, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.#ctor(System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional priority As Nullable(Of Integer) = null, Optional onAllTasksComplete As Nullable(Of OnAllTasksComplete) = null, Optional constraints As JobConstraints = null, Optional poolInfo As PoolInformation = null, Optional metadata As IList(Of MetadataItem) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter : Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.PoolInformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter (priority, onAllTasksComplete, constraints, poolInfo, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="priority">Die Priorität des Auftrags.</param>
        <param name="onAllTasksComplete">Sollte der Batch-Dienst Maßnahmen, wenn alle Aufgaben im Auftrag in den Zustand abgeschlossen sind.</param>
        <param name="constraints">Die ausführungseinschränkungen für den Auftrag.</param>
        <param name="poolInfo">Der Pool, auf dem der Batch-Dienst den Auftrag Aufgaben ausgeführt wird.</param>
        <param name="metadata">Eine Liste von Name / Wert-Paaren, die dem Auftrag als Metadaten zugeordnet.</param>
        <summary>
            Initialisiert eine neue Instanz der JobPatchParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ausführungseinschränkungen für den Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, unverändert die vorhandene Ausführung, die Einschränkungen übrig sind.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Metadata" />
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
            Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Auftrag als Metadaten zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, die Metadaten der vorhandenen Auftrag verbleibt unverändert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onAllTasksComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Aktion der Batch-Dienst ausgeführt werden sollen, wenn alle Aufgaben im Auftrag in den Zustand abgeschlossen sind.
            </summary>
        <value>To be added.</value>
        <remarks>
            Ohne Angabe wird das Verhalten der Abschluss bleibt unverändert. Sie möglicherweise nicht den Wert von TerminateJob ändern, um "NoAction" – d. h., nachdem Sie die automatische Auftrag beenden beteiligt sind, Sie nicht deaktiviert werden erneut aus. Wenn Sie dies versuchen, wird die Anforderung eine Fehlerantwort 'Ungültiger Eigenschaftswert'; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung). Folgende Werte sind möglich: 'NoAction', 'TerminateJob'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.PoolInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Pool, auf dem der Batch-Dienst den Auftrag Aufgaben ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Nur, wenn der Auftrag deaktiviert ist, können Sie den Pool für einen Auftrag ändern.
            Der Patch Auftrag Aufruf schlägt fehl, wenn Sie das PoolInfo-Element enthalten, und der Auftrag ist nicht deaktiviert. Wenn Sie eine AutoPoolSpecification-Spezifikation in der PoolInfo angeben, nur das "Keepalive" Eigenschaft kann aktualisiert werden, und klicken Sie dann nur, wenn Sie der automatischen Pool eine PoolLifetimeOption des Auftrags ist. Wenn nicht angegeben, wird der Auftrag zur Ausführung auf dem aktuellen Pool fortgesetzt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Priorität des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität. Wenn nicht angegeben, wird die Priorität des Auftrags bleibt unverändert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPatchParameter.Validate " />
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
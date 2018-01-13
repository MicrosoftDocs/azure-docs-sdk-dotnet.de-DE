<Type Name="PoolInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolInformation">
  <TypeSignature Language="C#" Value="public class PoolInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolInformation" />
  <TypeSignature Language="F#" Value="type PoolInformation = class" />
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
            Gibt an, wie ein Auftrag zu einem Pool zugewiesen werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.#ctor" />
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
            Initialisiert eine neue Instanz der PoolInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolInformation (string poolId = null, Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification autoPoolSpecification = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string poolId, class Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification autoPoolSpecification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolInformation : string * Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolInformation (poolId, autoPoolSpecification)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoPoolSpecification" Type="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification" />
      </Parameters>
      <Docs>
        <param name="poolId">Die ID des einen vorhandenen Pool. Alle Aufgaben des Auftrags werden auf dem angegebenen Pool ausgeführt.</param>
        <param name="autoPoolSpecification">Merkmale für eine temporäre "Pools". Der Batch-Dienst wird diese Pools erstellt, wenn der Auftrag übermittelt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der PoolInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification AutoPoolSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification AutoPoolSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.AutoPoolSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolSpecification As AutoPoolSpecification" />
      <MemberSignature Language="F#" Value="member this.AutoPoolSpecification : Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolInformation.AutoPoolSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoPoolSpecification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Eigenschaften für einen temporären "Pools". Der Batch-Dienst wird diese Pools erstellt, wenn der Auftrag übermittelt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Fällt die Erstellung des automatischen Pools, der Batch-Dienst verschiebt den Auftrag, um den Status "abgeschlossen", und der Fehler beim Erstellen des Anwendungspools in den Auftrag planen Error-Eigenschaft festgelegt wird. Der Batch-Dienst verwaltet die Lebensdauer (sowohl die Erstellung und, es sei denn, "Keepalive" angegeben ist, löschen) des automatischen Pools. Alle Benutzeraktionen, die Einfluss auf die Lebensdauer des Pools, während der Auftrag aktiv ist, werden zu unerwartetem Verhalten führen.
            Sie müssen die Pool-ID oder die Spezifikation des automatischen Pools, aber nicht beides angeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des einen vorhandenen Pool. Alle Aufgaben des Auftrags werden auf dem angegebenen Pool ausgeführt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Sie müssen sicherstellen, dass der Pool verwiesen wird, die von dieser Eigenschaft vorhanden ist.
            Wenn der Pool nicht, wenn der Batch-Dienst versucht vorhanden ist, einen Auftrag zu planen wird, werden keine Vorgänge für den Auftrag ausgeführt, bis Sie einen Pool mit dieser Id erstellt. Beachten Sie, dass der Batch-Dienst die Anforderung nicht abgelehnt werden. Sie wird Tasks einfach nicht ausgeführt, bis der Pool vorhanden ist.
            Sie müssen die Pool-ID oder die Spezifikation des automatischen Pools, aber nicht beides angeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolInformation.Validate " />
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
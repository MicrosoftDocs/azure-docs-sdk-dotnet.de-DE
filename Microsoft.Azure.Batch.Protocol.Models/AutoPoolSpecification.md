<Type Name="AutoPoolSpecification" FullName="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification">
  <TypeSignature Language="C#" Value="public class AutoPoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoPoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoPoolSpecification" />
  <TypeSignature Language="F#" Value="type AutoPoolSpecification = class" />
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
            Gibt die Eigenschaften für eine temporäre "Pools". Der Batch-Dienst wird diese Pools erstellt, wenn der Auftrag übermittelt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoPoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.#ctor" />
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
            Initialisiert eine neue Instanz der AutoPoolSpecification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoPoolSpecification (Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption poolLifetimeOption, string autoPoolIdPrefix = null, Nullable&lt;bool&gt; keepAlive = null, Microsoft.Azure.Batch.Protocol.Models.PoolSpecification pool = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption poolLifetimeOption, string autoPoolIdPrefix, valuetype System.Nullable`1&lt;bool&gt; keepAlive, class Microsoft.Azure.Batch.Protocol.Models.PoolSpecification pool) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.#ctor(Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.PoolSpecification)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification : Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.PoolSpecification -&gt; Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification" Usage="new Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification (poolLifetimeOption, autoPoolIdPrefix, keepAlive, pool)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolLifetimeOption" Type="Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption" />
        <Parameter Name="autoPoolIdPrefix" Type="System.String" />
        <Parameter Name="keepAlive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolSpecification" />
      </Parameters>
      <Docs>
        <param name="poolLifetimeOption">Die minimale Lebensdauer der automatisch erstellten Pools und wie mehrere Aufträge nach einem Zeitplan, die den Pools zugewiesen werden.</param>
        <param name="autoPoolIdPrefix">Ein Präfix, das den eindeutigen Bezeichner hinzugefügt, wenn ein Pool automatisch erstellt wird.</param>
        <param name="keepAlive">Ob einen automatischer Pool nach Ablauf der Lebensdauer aufrechtzuerhalten.</param>
        <param name="pool">Die poolspezifikation für den automatischen Pool.</param>
        <summary>
            Initialisiert eine neue Instanz der AutoPoolSpecification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolIdPrefix">
      <MemberSignature Language="C#" Value="public string AutoPoolIdPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoPoolIdPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.AutoPoolIdPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolIdPrefix As String" />
      <MemberSignature Language="F#" Value="member this.AutoPoolIdPrefix : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.AutoPoolIdPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoPoolIdPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Präfix für den eindeutigen Bezeichner hinzugefügt, wenn ein Pool automatisch erstellt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Batch-Dienst weist jedem Pool automatisch einen eindeutigen Bezeichner bei der Erstellung. Um für unterschiedliche Zwecke erstellten Ressourcenpools unterscheiden, können Sie angeben, dieses Element aus, um die ID ein Präfix hinzuzufügen, die zugewiesen wird. Das Präfix kann bis zu 20 Zeichen lang sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAlive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; KeepAlive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; KeepAlive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.KeepAlive" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAlive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.KeepAlive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.KeepAlive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keepAlive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob einen automatischer Pool nach Ablauf der Lebensdauer aufrechtzuerhalten.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn "false", löscht der Batch-Dienst den Pool nach Ablauf der Lebensdauer (wie durch die Einstellung PoolLifetimeOption bestimmt); Wenn der Auftrag oder den Auftrag zu planen, also abgeschlossen wird. Bei "true", wird der Batch-Dienst den Pool nicht automatisch gelöscht. Es liegt im Ermessen der Benutzer automatisch Pools, die mit dieser Option erstellte zu löschen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Pool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolSpecification Pool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolSpecification Pool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.Pool" />
      <MemberSignature Language="VB.NET" Value="Public Property Pool As PoolSpecification" />
      <MemberSignature Language="F#" Value="member this.Pool : Microsoft.Azure.Batch.Protocol.Models.PoolSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.Pool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die poolspezifikation für den automatischen Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolLifetimeOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption PoolLifetimeOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption PoolLifetimeOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolLifetimeOption As PoolLifetimeOption" />
      <MemberSignature Language="F#" Value="member this.PoolLifetimeOption : Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolLifetimeOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die minimale Lebensdauer der erstellten automatisch Pools und wie mehrere Aufträge nach einem Zeitplan, die den Pools zugewiesen werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "JobSchedule", "Projekt"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoPoolSpecification.Validate " />
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
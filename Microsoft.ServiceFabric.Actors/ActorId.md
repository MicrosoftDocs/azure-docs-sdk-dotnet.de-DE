<Type Name="ActorId" FullName="Microsoft.ServiceFabric.Actors.ActorId">
  <TypeSignature Language="C#" Value="public sealed class ActorId : IComparable&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;, IEquatable&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorId extends System.Object implements class System.IComparable`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;, class System.IEquatable`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.ActorId" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorId&#xA;Implements IComparable(Of ActorId), IEquatable(Of ActorId)" />
  <TypeSignature Language="F#" Value="type ActorId = class&#xA;    interface IEquatable&lt;ActorId&gt;&#xA;    interface IComparable&lt;ActorId&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ActorId")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Der Akteur-ID stellt die Identität der Akteur innerhalb eines Diensts Akteur dar. Dies dient zum Identifizieren der Partitions des Diensts Akteur innerhalb der Akteur ausgeführt wird, finden Sie unter<see cref="M:Microsoft.ServiceFabric.Actors.ActorId.GetPartitionKey" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorId (Guid id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.#ctor(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As Guid)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ActorId : Guid -&gt; Microsoft.ServiceFabric.Actors.ActorId" Usage="new Microsoft.ServiceFabric.Actors.ActorId id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="id">Für die Akteur-Id-Wert.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse der Akteur-ID mit der Id-Wert des Typs <see cref="T:System.Guid" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorId (long id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ActorId : int64 -&gt; Microsoft.ServiceFabric.Actors.ActorId" Usage="new Microsoft.ServiceFabric.Actors.ActorId id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="id">Für die Akteur-Id-Wert.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse der Akteur-ID mit der Id-Wert des Typs <see cref="T:System.Int64" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorId (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ActorId : string -&gt; Microsoft.ServiceFabric.Actors.ActorId" Usage="new Microsoft.ServiceFabric.Actors.ActorId id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Für die Akteur-Id-Wert.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse der Akteur-ID mit der Id-Wert des Typs <see cref="T:System.String" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (Microsoft.ServiceFabric.Actors.ActorId other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(class Microsoft.ServiceFabric.Actors.ActorId other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.CompareTo(Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As ActorId) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : Microsoft.ServiceFabric.Actors.ActorId -&gt; int&#xA;override this.CompareTo : Microsoft.ServiceFabric.Actors.ActorId -&gt; int" Usage="actorId.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="other">Der Akteur-ID, die mit dieser Instanz verglichen werden soll. </param>
        <summary>
            Vergleicht diese Instanz mit einem angegebenen <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> -Objekt und gibt an, ob diese Instanz vorausgeht, späteren oder derselben Position in der Sortierreihenfolge als der angegebene Akteur-ID angezeigt wird. 
            </summary>
        <returns>Eine 32-Bit-Ganzzahl mit Vorzeichen, die angibt, ob diese Instanz vorausgeht, späteren oder derselben Position in der Sortierreihenfolge als der andere Parameter angezeigt wird.</returns>
        <remarks>Der Vergleich erfolgt basierend auf die Id, wenn beide Instanzen die gleiche haben <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />.
            Wenn <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> ungleich sind, und anschließend der Vergleich erfolgt basierend auf Zeichenfolgendarstellung der Akteur-Id ist.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRandom">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.ActorId CreateRandom ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.ActorId CreateRandom() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.CreateRandom" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateRandom () As ActorId" />
      <MemberSignature Language="F#" Value="static member CreateRandom : unit -&gt; Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.ActorId.CreateRandom " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellen Sie eine neue Instanz der dem <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> Art <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" /> mit einer zufälligen <see cref="T:System.Int64" /> Id-Wert. 
            </summary>
        <returns>Ein neues Akteur-ID-Objekt.</returns>
        <remarks>Diese Methode ist threadsicher und generiert einen neuen zufälligen <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> jedes Mal, wenn sie aufgerufen wird.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.ServiceFabric.Actors.ActorId other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.ServiceFabric.Actors.ActorId other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.Equals(Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As ActorId) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.ServiceFabric.Actors.ActorId -&gt; bool" Usage="actorId.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="other">Der Akteur-ID, die mit dieser Instanz verglichen werden soll. </param>
        <summary>
            Bestimmt, ob diese Instanz und ein anderes angegebenes <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />-Objekt denselben Wert haben.
            </summary>
        <returns>True, wenn die <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> und Id, von dem anderen Parameter entspricht der <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> und die Id dieser Instanz, andernfalls "false". Wenn andere null ist, gibt die Methode "false" zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="actorId.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">Der Akteur-ID, die mit dieser Instanz verglichen werden soll. </param>
        <summary>
            Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />-Objekt sein muss, denselben Wert haben. Überschreibt <see cref="M:System.Object.Equals(System.Object)" />.
            </summary>
        <returns>"true", wenn Obj ist ein <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> ist und denselben Wert wie diese Instanz hat; andernfalls "false". Wenn Obj null ist, gibt die Methode "false" zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGuidId">
      <MemberSignature Language="C#" Value="public Guid GetGuidId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Guid GetGuidId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetGuidId" />
      <MemberSignature Language="VB.NET" Value="Public Function GetGuidId () As Guid" />
      <MemberSignature Language="F#" Value="member this.GetGuidId : unit -&gt; Guid" Usage="actorId.GetGuidId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Id für die der Akteur-ID ab, deren <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> ist <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" />.
            </summary>
        <returns>
          <see cref="T:System.Guid" />Für die der Akteur-ID Id-Wert.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Die <see cref="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" /> nicht<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" /></exception>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="actorId.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überschreibt <see cref="M:System.Object.GetHashCode" />.
            </summary>
        <returns>Der Hashcode für das aktuelle Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLongId">
      <MemberSignature Language="C#" Value="public long GetLongId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 GetLongId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetLongId" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLongId () As Long" />
      <MemberSignature Language="F#" Value="member this.GetLongId : unit -&gt; int64" Usage="actorId.GetLongId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Id für die der Akteur-ID ab, deren <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> ist <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" />.
            </summary>
        <returns>
          <see cref="T:System.Int64" />Für die der Akteur-ID Id-Wert.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Die <see cref="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" /> nicht<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" /></exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public long GetPartitionKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 GetPartitionKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionKey () As Long" />
      <MemberSignature Language="F#" Value="member this.GetPartitionKey : unit -&gt; int64" Usage="actorId.GetPartitionKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft den Partitionsschlüssel für diese Akteur-ID ab.
            </summary>
        <returns>Der Schlüssel für die Suche nach der Partition des Akteurs-Diensts, der für diese Akteur-ID zuständig ist.</returns>
        <remarks>
          <list type="bullet">
            <item>Der Akteur-Dienst ist immer mit partitioniert <see cref="F:System.Fabric.Description.PartitionScheme.UniformInt64Range" /> Schema. Aus diesem Grund ist der Partitionsschlüssel der <see cref="T:System.Int64" /> Typ.</item>
            <item>Der Partitionsschlüssel wird generiert, die auf der Grundlage der <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> und den Id-Wert wie folgt: <list type="bullet"> <item> <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.String" />: CRC64-Hash der UTF8 Bytes für die Zeichenfolgen-ID</item> <item> <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" />: CRC64-Hash der Bytes der Guid-id.</item> <item> <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" />: Tatsächlichen Wert der lang Id.</item></list></item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStringId">
      <MemberSignature Language="C#" Value="public string GetStringId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetStringId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetStringId" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStringId () As String" />
      <MemberSignature Language="F#" Value="member this.GetStringId : unit -&gt; string" Usage="actorId.GetStringId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Id für die der Akteur-ID ab, deren <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> ist <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.String" />.
            </summary>
        <returns>
          <see cref="T:System.String" />Für die der Akteur-ID Id-Wert.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Die <see cref="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" /> nicht<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" /></exception>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorIdKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.ActorIdKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ActorIdKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.ServiceFabric.Actors.ActorIdKind" Usage="Microsoft.ServiceFabric.Actors.ActorId.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorIdKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> für die der Akteur-ID.
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />für die der Akteur-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.ServiceFabric.Actors.ActorId x, Microsoft.ServiceFabric.Actors.ActorId y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.ServiceFabric.Actors.ActorId x, class Microsoft.ServiceFabric.Actors.ActorId y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.op_Equality(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (x As ActorId, y As ActorId) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.ActorId -&gt; bool" Usage="x = y" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="y" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="x">Die erste Akteur-ID verglichen werden soll, oder null. </param>
        <param name="y">Die zweite Akteur-ID verglichen werden soll, oder null. </param>
        <summary>
            Bestimmt, ob zwei angegebene ActorIds haben die gleiche Id und <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />.
            </summary>
        <returns>True, wenn die Id und <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> für beide Objekte denselben ist, andernfalls "false" ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.ServiceFabric.Actors.ActorId x, Microsoft.ServiceFabric.Actors.ActorId y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.ServiceFabric.Actors.ActorId x, class Microsoft.ServiceFabric.Actors.ActorId y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.op_Inequality(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (x As ActorId, y As ActorId) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.ActorId -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.ActorId.op_Inequality (x, y)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="y" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="x">Die erste Akteur-ID verglichen werden soll, oder null. </param>
        <param name="y">Die zweite Akteur-ID verglichen werden soll, oder null. </param>
        <summary>
            Bestimmt, ob zwei angegebene ActorIds haben unterschiedliche Werte für die Id und <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />.
            </summary>
        <returns>True, wenn die Id oder <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> für beide Objekte unterschiedlich ist, andernfalls "true" ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="actorId.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überschreibt <see cref="M:System.Object.ToString" />.
            </summary>
        <returns>Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
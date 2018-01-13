<Type Name="Epoch" FullName="System.Fabric.Epoch">
  <TypeSignature Language="C#" Value="public struct Epoch : IComparable&lt;System.Fabric.Epoch&gt;, IEquatable&lt;System.Fabric.Epoch&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi serializable sealed beforefieldinit Epoch extends System.ValueType implements class System.IComparable`1&lt;valuetype System.Fabric.Epoch&gt;, class System.IEquatable`1&lt;valuetype System.Fabric.Epoch&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Epoch" />
  <TypeSignature Language="VB.NET" Value="Public Structure Epoch&#xA;Implements IComparable(Of Epoch), IEquatable(Of Epoch)" />
  <TypeSignature Language="F#" Value="type Epoch = struct" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;System.Fabric.Epoch&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;System.Fabric.Epoch&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para> Stellt die aktuelle Version der Service Fabric-Partition an. </para>
    </summary>
    <remarks>
      <para>Ein Epoche ist eine Konfigurationsnummer für die Partition als Ganzes. Wenn die Konfiguration des Replikats Änderungen, z. B. wenn das primäre Replikat ändert, die Vorgänge, die vom neuen primären Replikat repliziert werden als sind eine neue Epoche aus. der von dem alten primären Replikat gesendet wurden festgelegt. Die Tatsache, die dass das primäre geändert hat ist nicht direkt sichtbar auf sekundäre Replikate, die nicht durch einen Fehler in der Regel betroffen sind, die das ursprüngliche primäre Replikat betroffen. Um nachzuverfolgen, dass sich das primäre Replikat geändert wurde, an das sekundäre Replikat übertragen werden. Diese Kommunikation erfolgt über die <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> Methode. Die meisten Dienste können die Details der inneren Felder der Epoche ignorieren, wie es in der Regel ausreichend ist, zu wissen, dass es sich bei Beginn des Zeitraums geändert hat und Epochs, um zu bestimmen, relative Reihenfolge der Vorgänge und-Ereignisse im System zu vergleichen. Zu diesem Zweck sind Vergleichsoperationen bereitgestellt.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Epoch (long dataLossNumber, long configurationNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 dataLossNumber, int64 configurationNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dataLossNumber As Long, configurationNumber As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Epoch : int64 * int64 -&gt; System.Fabric.Epoch" Usage="new System.Fabric.Epoch (dataLossNumber, configurationNumber)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataLossNumber" Type="System.Int64" />
        <Parameter Name="configurationNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="dataLossNumber">
          <para>Ein <see cref="T:System.Int64" /> , der einem zunehmenden entspricht, das aktualisiert wird, wenn Datenverlust vermutet wird.</para>
        </param>
        <param name="configurationNumber">
          <para>Ein <see cref="T:System.Int64" /> , der einem zunehmenden entspricht, die aktualisiert wird, sobald die Konfiguration dieses Replikats Änderungen festgelegt.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Epoch" /> Klasse mit dem angegebenen datenverlustnummer und Konfigurationsnummer.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (System.Fabric.Epoch other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(valuetype System.Fabric.Epoch other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.CompareTo(System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As Epoch) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : System.Fabric.Epoch -&gt; int&#xA;override this.CompareTo : System.Fabric.Epoch -&gt; int" Usage="epoch.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>Die <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <summary>
          <para>Vergleicht dieses <see cref="T:System.Fabric.Epoch" /> Objekt mit dem angegebenen <paramref name="other" /> <see cref="T:System.Fabric.Epoch" /> Objekt.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Int32" />zurück.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationNumber">
      <MemberSignature Language="C#" Value="public long ConfigurationNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConfigurationNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Epoch.ConfigurationNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigurationNumber As Long" />
      <MemberSignature Language="F#" Value="member this.ConfigurationNumber : int64 with get, set" Usage="System.Fabric.Epoch.ConfigurationNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die aktuelle Konfigurationseigenschaft in dieser <see cref="T:System.Fabric.Epoch" />.</para>
        </summary>
        <value>
          <para>Gibt eine <see cref="T:System.Int64" /> , der die Konfigurationsnummer darstellt.</para>
        </value>
        <remarks>
          <para>Die Konfigurationsnummer ist eine zunehmende-Wert, der aktualisiert wird, sobald die Konfiguration dieses Replikats Änderungen festgelegt. Die Dienste werden informiert, wenn der aktuellen Konfiguration Nummer nur, wenn <see cref="M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" /> Methode wird aufgerufen, als Ergebnis der Versuch, das primäre Replikat der Replikatgruppe ändern.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLossNumber">
      <MemberSignature Language="C#" Value="public long DataLossNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DataLossNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Epoch.DataLossNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLossNumber As Long" />
      <MemberSignature Language="F#" Value="member this.DataLossNumber : int64 with get, set" Usage="System.Fabric.Epoch.DataLossNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die aktuelle datenverlustnummer in dieser <see cref="T:System.Fabric.Epoch" />.</para>
        </summary>
        <value>
          <para>Gibt eine <see cref="T:System.Int64" /> , die die aktuelle datenverlustnummer darstellt.</para>
        </value>
        <remarks>
          <para>Die Daten verloren gehen Number-Eigenschaft ist eine zunehmende Wert, der aktualisiert wird, wenn Datenverlust vermutet wird, als beim Verlust des ein Quorum der Replikate im Replikat festgelegt, die das primäre Replikat enthält, an.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (System.Fabric.Epoch other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(valuetype System.Fabric.Epoch other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.Equals(System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : System.Fabric.Epoch -&gt; bool" Usage="epoch.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>Das Objekt, das mit dem aktuellen <see cref="T:System.Fabric.Epoch" />-Objekt verglichen werden soll.</para>
        </param>
        <summary>
          <para>Bestimmt, ob das angegebene <see cref="T:System.Fabric.Epoch" /> Objekt gleich der aktuellen <see cref="T:System.Fabric.Epoch" /> Objekt.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn das angegebene <see cref="T:System.Fabric.Epoch" /> Objekt gleich der aktuellen <see cref="T:System.Fabric.Epoch" /> Objekt; andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="epoch.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">
          <para>Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</para>
        </param>
        <summary>
          <para>Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> ist das angegebene Objekt mit dem aktuellen Objekt identisch ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="epoch.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Dient als Hashfunktion für die <see cref="T:System.Fabric.Epoch" /> Typ.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Int32" /> , das einen Hashcode für die aktuelle darstellt <see cref="T:System.Fabric.Epoch" />...</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_Equality(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left = right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <param name="right">
          <para>Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <summary>
          <para>Bestimmt, ob zwei angegebene <see cref="T:System.Fabric.Epoch" />-Objekte denselben Wert haben.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> entspricht der Wert der <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThan">
      <MemberSignature Language="C#" Value="public static bool operator &gt; (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThan(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_GreaterThan(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt; (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt; ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &gt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <param name="right">
          <para>Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <summary>
          <para>Bestimmt, ob ein angegebener <see cref="T:System.Fabric.Epoch" /> -Quellobjekt ist größer als ein anderer angegebener <see cref="T:System.Fabric.Epoch" /> Objekt.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> ist größer als der Wert der <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &gt;= (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThanOrEqual(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_GreaterThanOrEqual(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt;= (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt;= ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &gt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <param name="right">
          <para>Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <summary>
          <para>Bestimmt, ob ein angegebener <see cref="T:System.Fabric.Epoch" /> Objekt ist größer als oder gleich einem anderen angegebenen <see cref="T:System.Fabric.Epoch" /> Objekt.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> ist größer als oder gleich dem Wert der <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_Inequality(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="System.Fabric.Epoch.op_Inequality (left, right)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <param name="right">
          <para>Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <summary>
          <para>Bestimmt, ob zwei angegebene <see cref="T:System.Fabric.Epoch" /> -Objekte verschiedene Werte haben.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> unterscheidet sich der Wert der <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThan">
      <MemberSignature Language="C#" Value="public static bool operator &lt; (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThan(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_LessThan(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt; (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt; ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &lt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <param name="right">
          <para>Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <summary>
          <para>Bestimmt, ob ein angegebener <see cref="T:System.Fabric.Epoch" /> -Objekts kleiner ist als ein anderer angegebener <see cref="T:System.Fabric.Epoch" /> Objekt.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> ist kleiner als der Wert des <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &lt;= (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThanOrEqual(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_LessThanOrEqual(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt;= (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt;= ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &lt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para>Links <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <param name="right">
          <para>Das Recht <see cref="T:System.Fabric.Epoch" /> zu vergleichende Objekt.</para>
        </param>
        <summary>
          <para>Bestimmt, ob ein angegebener <see cref="T:System.Fabric.Epoch" /> Objekt ist kleiner oder gleich einem anderen angegebenen <see cref="T:System.Fabric.Epoch" /> Objekt.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn der Wert der <paramref name="left" /> ist kleiner oder gleich dem Wert des <paramref name="right" />ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
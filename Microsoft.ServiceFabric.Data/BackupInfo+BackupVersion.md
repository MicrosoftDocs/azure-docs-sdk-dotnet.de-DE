<Type Name="BackupInfo+BackupVersion" FullName="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion">
  <TypeSignature Language="C#" Value="public struct BackupInfo.BackupVersion : IComparable&lt;Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion&gt;, IEquatable&lt;Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion&gt;" />
  <TypeSignature Language="ILAsm" Value=".class nested public sequential ansi sealed beforefieldinit BackupInfo/BackupVersion extends System.ValueType implements class System.IComparable`1&lt;valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion&gt;, class System.IEquatable`1&lt;valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" />
  <TypeSignature Language="VB.NET" Value="Public Structure BackupInfo.BackupVersion&#xA;Implements IComparable(Of BackupInfo.BackupVersion), IEquatable(Of BackupInfo.BackupVersion)" />
  <TypeSignature Language="F#" Value="type BackupInfo.BackupVersion = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Performance", "CA1815")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt die Version der Sicherung dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVersion (System.Fabric.Epoch epoch, long lsn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Epoch epoch, int64 lsn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.#ctor(System.Fabric.Epoch,System.Int64)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion : System.Fabric.Epoch * int64 -&gt; Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" Usage="new Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion (epoch, lsn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="lsn" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="epoch">Die <cref name="Epoch" /> an dem die Sicherung erstellt wurde.</param>
        <param name="lsn">Die letzte committed logischen Sequenznummer, die in der Sicherung enthalten.</param>
        <summary>
            Initialisiert eine neue Instanz der dem<cref name="BackupVersion" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.CompareTo(Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As BackupInfo.BackupVersion) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion -&gt; int&#xA;override this.CompareTo : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion -&gt; int" Usage="backupVersion.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
      </Parameters>
      <Docs>
        <param name="other">Ein Objekt, das als <cref name="BackupVersion" /> ausgewertet wird.</param>
        <summary>
            Vergleicht diese Instanz mit einem angegebenen <cref name="BackupVersion" /> -Objekt und gibt an, ob diese Instanz vorausgeht, späteren oder derselben Position wie das angegebene in der Sortierreihenfolge angezeigt <cref name="BackupVersion" />. 
            </summary>
        <returns>
            Ein Wert, der die relative Reihenfolge der verglichenen Objekte angibt.
            Kleiner als 0 (null) gibt an, dass diese Instanz in der Sortierreihenfolge andere vorausgeht.
            0 (null) gibt an, dass diese Instanz in der gleichen Position in der Sortierreihenfolge wie andere auftritt. Größer als 0 (null) gibt an, dass diese Instanz in der Sortierreihenfolge andere folgt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public System.Fabric.Epoch Epoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Epoch Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Epoch As Epoch" />
      <MemberSignature Language="F#" Value="member this.Epoch : System.Fabric.Epoch" Usage="Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Epoch</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <cref name="Epoch" /> an dem die Sicherung erstellt wurde.
            </summary>
        <value>Die <cref name="Epoch" /> an dem die Sicherung erstellt wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Equals(Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As BackupInfo.BackupVersion) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion -&gt; bool" Usage="backupVersion.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion" />
      </Parameters>
      <Docs>
        <param name="other">Die <cref name="BackupVersion" /> dieser Instanz verglichen werden soll. </param>
        <summary>
            Bestimmt, ob diese Instanz und ein anderes angegebenes <cref name="BackupVersion" />-Objekt denselben Wert haben.
            </summary>
        <returns>
            "true", wenn der Wert des Value-Parameters den Wert dieser Instanz identisch ist; andernfalls "false". 
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="backupVersion.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">Die <cref name="BackupVersion" /> dieser Instanz verglichen werden soll. </param>
        <summary>
            Bestimmt, ob diese Instanz und ein anderes angegebenes <cref name="BackupVersion" />-Objekt denselben Wert haben.
            </summary>
        <returns>
            "true", wenn der Wert des Value-Parameters den Wert dieser Instanz identisch ist; andernfalls "false". 
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="backupVersion.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt den Hashcode für diesen <cref name="BackupVersion" /> zurück.
            </summary>
        <returns>
            Ein 32-Bit-Hashcode als ganze Zahl mit Vorzeichen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvalidBackupVersion">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion InvalidBackupVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype Microsoft.ServiceFabric.Data.BackupInfo/BackupVersion InvalidBackupVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.InvalidBackupVersion" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly InvalidBackupVersion As BackupInfo.BackupVersion " />
      <MemberSignature Language="F#" Value=" staticval mutable InvalidBackupVersion : Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion" Usage="Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.InvalidBackupVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupInfo+BackupVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ungültige Version der Sicherung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lsn">
      <MemberSignature Language="C#" Value="public long Lsn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Lsn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Lsn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Lsn As Long" />
      <MemberSignature Language="F#" Value="member this.Lsn : int64" Usage="Microsoft.ServiceFabric.Data.BackupInfo.BackupVersion.Lsn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ein Commit der letzten logischen Sequenznummer, die in der Sicherung enthalten.
            </summary>
        <value>Die letzte committed logischen Sequenznummer, die in der Sicherung enthalten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
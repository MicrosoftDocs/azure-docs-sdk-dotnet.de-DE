<Type Name="ServicePartitionKind" FullName="System.Fabric.ServicePartitionKind">
  <TypeSignature Language="C#" Value="public enum ServicePartitionKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServicePartitionKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServicePartitionKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServicePartitionKind" />
  <TypeSignature Language="F#" Value="type ServicePartitionKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt den Typ des Partitionierungsschemas an, die verwendet wird. </para>
    </summary>
    <remarks>
      <para>
        <see cref="T:System.Fabric.ServicePartitionKind" />definiert den Wert des der <see cref="P:System.Fabric.ServicePartitionInformation.Kind" /> Eigenschaft von der <see cref="T:System.Fabric.ServicePartitionInformation" /> Klasse.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Int64Range">
      <MemberSignature Language="C#" Value="Int64Range" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ServicePartitionKind Int64Range = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ServicePartitionKind.Int64Range" />
      <MemberSignature Language="VB.NET" Value="Int64Range" />
      <MemberSignature Language="F#" Value="Int64Range = 2" Usage="System.Fabric.ServicePartitionKind.Int64Range" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Partition auf Int64-Schlüsselbereichen basiert und eine <see cref="T:System.Fabric.Int64RangePartitionInformation" /> -Objekt, das ursprünglich über erstellt wurde <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ServicePartitionKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ServicePartitionKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.ServicePartitionKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Partitionsart ungültig ist.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Named">
      <MemberSignature Language="C#" Value="Named" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ServicePartitionKind Named = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ServicePartitionKind.Named" />
      <MemberSignature Language="VB.NET" Value="Named" />
      <MemberSignature Language="F#" Value="Named = 3" Usage="System.Fabric.ServicePartitionKind.Named" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Partition auf Zeichenfolgennamen basiert und eine <see cref="T:System.Fabric.NamedPartitionInformation" /> -Objekt, das ursprünglich über erstellt wurde <see cref="T:System.Fabric.Description.NamedPartitionSchemeDescription" />.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Singleton">
      <MemberSignature Language="C#" Value="Singleton" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ServicePartitionKind Singleton = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ServicePartitionKind.Singleton" />
      <MemberSignature Language="VB.NET" Value="Singleton" />
      <MemberSignature Language="F#" Value="Singleton = 1" Usage="System.Fabric.ServicePartitionKind.Singleton" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Partition auf Zeichenfolgennamen basiert und eine <see cref="T:System.Fabric.SingletonPartitionInformation" /> -Objekt, das ursprünglich über erstellt wurde <see cref="T:System.Fabric.Description.SingletonPartitionSchemeDescription" />.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="PartitionScheme" FullName="System.Fabric.Description.PartitionScheme">
  <TypeSignature Language="C#" Value="public enum PartitionScheme" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PartitionScheme extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PartitionScheme" />
  <TypeSignature Language="VB.NET" Value="Public Enum PartitionScheme" />
  <TypeSignature Language="F#" Value="type PartitionScheme = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Listet die Verfahren, die ein Dienst partitioniert werden kann.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.PartitionScheme Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.PartitionScheme.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.PartitionScheme.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionScheme</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Alle Service Fabric-Enumerationen reservieren Sie den Wert "Ungültig".</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Named">
      <MemberSignature Language="C#" Value="Named" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.PartitionScheme Named = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.PartitionScheme.Named" />
      <MemberSignature Language="VB.NET" Value="Named" />
      <MemberSignature Language="F#" Value="Named = 3" Usage="System.Fabric.Description.PartitionScheme.Named" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionScheme</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Dienst mit dem Namen partitioniert ist. Dies bedeutet, dass jede Partition mit einem Zeichenfolgennamen zugeordnet ist.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Singleton">
      <MemberSignature Language="C#" Value="Singleton" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.PartitionScheme Singleton = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.PartitionScheme.Singleton" />
      <MemberSignature Language="VB.NET" Value="Singleton" />
      <MemberSignature Language="F#" Value="Singleton = 1" Usage="System.Fabric.Description.PartitionScheme.Singleton" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionScheme</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Dienst Singleton partitioniert ist. Dies bedeutet, dass nur eine Partition vorhanden ist, oder der Dienst ist nicht partitioniert.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="UniformInt64Range">
      <MemberSignature Language="C#" Value="UniformInt64Range" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.PartitionScheme UniformInt64Range = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.PartitionScheme.UniformInt64Range" />
      <MemberSignature Language="VB.NET" Value="UniformInt64Range" />
      <MemberSignature Language="F#" Value="UniformInt64Range = 2" Usage="System.Fabric.Description.PartitionScheme.UniformInt64Range" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionScheme</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass der Dienst uniform int64 bereichspartitionierte. Dies bedeutet, dass jede Partition einen Bereich von Schlüsselwerten int64 besitzt.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>
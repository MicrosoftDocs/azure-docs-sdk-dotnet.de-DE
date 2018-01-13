<Type Name="ProgressUnitType" FullName="System.Fabric.ProgressUnitType">
  <TypeSignature Language="C#" Value="public enum ProgressUnitType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ProgressUnitType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ProgressUnitType" />
  <TypeSignature Language="VB.NET" Value="Public Enum ProgressUnitType" />
  <TypeSignature Language="F#" Value="type ProgressUnitType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Beschreibt die Maßeinheit für die einzelnen <see cref="M:System.Fabric.IImageStoreProgressHandler.UpdateProgress(System.Int64,System.Int64,System.Fabric.ProgressUnitType)" /> Rückruf.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Bytes">
      <MemberSignature Language="C#" Value="Bytes" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ProgressUnitType Bytes = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ProgressUnitType.Bytes" />
      <MemberSignature Language="VB.NET" Value="Bytes" />
      <MemberSignature Language="F#" Value="Bytes = 1" Usage="System.Fabric.ProgressUnitType.Bytes" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProgressUnitType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Die Maßeinheit wird in Bytes.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="Files" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ProgressUnitType Files = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ProgressUnitType.Files" />
      <MemberSignature Language="VB.NET" Value="Files" />
      <MemberSignature Language="F#" Value="Files = 3" Usage="System.Fabric.ProgressUnitType.Files" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProgressUnitType</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            Die Maßeinheit wird in Anzahl von Dateien.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ProgressUnitType Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ProgressUnitType.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.ProgressUnitType.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProgressUnitType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Für die interne Verwendung reserviert. Möglicherweise einen Konflikt zwischen verwalteten und systemeigenen DLL-Versionen.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServiceSubPackages">
      <MemberSignature Language="C#" Value="ServiceSubPackages" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ProgressUnitType ServiceSubPackages = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ProgressUnitType.ServiceSubPackages" />
      <MemberSignature Language="VB.NET" Value="ServiceSubPackages" />
      <MemberSignature Language="F#" Value="ServiceSubPackages = 2" Usage="System.Fabric.ProgressUnitType.ServiceSubPackages" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProgressUnitType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Die Maßeinheit wird in Anzahl von Code, Konfiguration und Datenpakete.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>
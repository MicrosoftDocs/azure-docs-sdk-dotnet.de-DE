<Type Name="ReconfigurationType" FullName="System.Fabric.ReconfigurationType">
  <TypeSignature Language="C#" Value="public enum ReconfigurationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ReconfigurationType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReconfigurationType" />
  <TypeSignature Language="VB.NET" Value="Public Enum ReconfigurationType" />
  <TypeSignature Language="F#" Value="type ReconfigurationType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Replikat-Neukonfiguration-Typ darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="Failover" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationType Failover = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationType.Failover" />
      <MemberSignature Language="VB.NET" Value="Failover" />
      <MemberSignature Language="F#" Value="Failover = 2" Usage="System.Fabric.ReconfigurationType.Failover" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Neukonfiguration ausgelöst, die als Antwort auf eine primäre ausfällt. Dies kann zahlreiche Ursachen wie z. B. primäres Replikat abstürzenden usw. sein.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationType None = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationType.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 4" Usage="System.Fabric.ReconfigurationType.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationType</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            Keine Neukonfiguration wird derzeit ausgeführt.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Other">
      <MemberSignature Language="C#" Value="Other" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationType Other = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationType.Other" />
      <MemberSignature Language="VB.NET" Value="Other" />
      <MemberSignature Language="F#" Value="Other = 3" Usage="System.Fabric.ReconfigurationType.Other" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationType</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            Neukonfigurationen, in der keine Änderung mit dem primären Replikat erfolgt.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="SwapPrimary">
      <MemberSignature Language="C#" Value="SwapPrimary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationType SwapPrimary = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationType.SwapPrimary" />
      <MemberSignature Language="VB.NET" Value="SwapPrimary" />
      <MemberSignature Language="F#" Value="SwapPrimary = 1" Usage="System.Fabric.ReconfigurationType.SwapPrimary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Neukonfiguration ausgelöst, um ein aktives sekundäres Replikat zur primären Rolle heraufstufen und Herabstufen vorhandenes primäres Replikat zur sekundären Rolle.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ReconfigurationType Unknown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ReconfigurationType.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 0" Usage="System.Fabric.ReconfigurationType.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Ungültige Neukonfiguration-Typ.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>
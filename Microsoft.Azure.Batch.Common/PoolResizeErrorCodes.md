<Type Name="PoolResizeErrorCodes" FullName="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes">
  <TypeSignature Language="C#" Value="public static class PoolResizeErrorCodes" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PoolResizeErrorCodes extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolResizeErrorCodes" />
  <TypeSignature Language="F#" Value="type PoolResizeErrorCodes = class" />
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
            Enthält die Fehlercodes, die spezifisch für Pool-Größe-Fehlern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccountCoreQuotaReached">
      <MemberSignature Language="C#" Value="public const string AccountCoreQuotaReached;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AccountCoreQuotaReached" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AccountCoreQuotaReached" />
      <MemberSignature Language="VB.NET" Value="Public Const AccountCoreQuotaReached As String " />
      <MemberSignature Language="F#" Value="val mutable AccountCoreQuotaReached : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AccountCoreQuotaReached" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Konto hat sein Kontingent von Compute-Knoten erreicht.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationFailed">
      <MemberSignature Language="C#" Value="public const string AllocationFailed;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AllocationFailed" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AllocationFailed" />
      <MemberSignature Language="VB.NET" Value="Public Const AllocationFailed As String " />
      <MemberSignature Language="F#" Value="val mutable AllocationFailed : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AllocationFailed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Fehler beim Versuch, die gewünschte Anzahl von Compute-Knoten zu reservieren.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationTimedOut">
      <MemberSignature Language="C#" Value="public const string AllocationTimedOut;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AllocationTimedOut" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AllocationTimedOut" />
      <MemberSignature Language="VB.NET" Value="Public Const AllocationTimedOut As String " />
      <MemberSignature Language="F#" Value="val mutable AllocationTimedOut : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AllocationTimedOut" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Batch-Dienst konnte die gewünschte Anzahl von Serverknoten innerhalb des Timeouts zum Ändern der Größe zuordnen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodesFailed">
      <MemberSignature Language="C#" Value="public const string RemoveNodesFailed;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RemoveNodesFailed" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.RemoveNodesFailed" />
      <MemberSignature Language="VB.NET" Value="Public Const RemoveNodesFailed As String " />
      <MemberSignature Language="F#" Value="val mutable RemoveNodesFailed : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.RemoveNodesFailed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Fehler beim Entfernen des Compute-Knoten aus dem Pool.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeStopped">
      <MemberSignature Language="C#" Value="public const string ResizeStopped;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ResizeStopped" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.ResizeStopped" />
      <MemberSignature Language="VB.NET" Value="Public Const ResizeStopped As String " />
      <MemberSignature Language="F#" Value="val mutable ResizeStopped : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.ResizeStopped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Benutzer beendet den Vorgang zum Ändern der Größe.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="public const string Unknown;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Unknown" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.Unknown" />
      <MemberSignature Language="VB.NET" Value="Public Const Unknown As String " />
      <MemberSignature Language="F#" Value="val mutable Unknown : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Ursache des Fehlers ist nicht bekannt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
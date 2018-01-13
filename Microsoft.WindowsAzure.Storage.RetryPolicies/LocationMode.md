<Type Name="LocationMode" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode">
  <TypeSignature Language="C#" Value="public enum LocationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed LocationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum LocationMode" />
  <TypeSignature Language="F#" Value="type LocationMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Gibt den Modus des Speicherorts, an welcher Stelle die Anforderung erhalten soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PrimaryOnly">
      <MemberSignature Language="C#" Value="PrimaryOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode PrimaryOnly = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryOnly" />
      <MemberSignature Language="VB.NET" Value="PrimaryOnly" />
      <MemberSignature Language="F#" Value="PrimaryOnly = 0" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Anforderungen werden stets an den primären Speicherort gesendet.
            </summary>
        <remarks>
            Wenn dieser Wert für Anforderungen, die nur für einen sekundären Standort (z. B. GetServiceStats) funktionieren verwendet wird, schlägt die Anforderung des Clients fehl.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryThenSecondary">
      <MemberSignature Language="C#" Value="PrimaryThenSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode PrimaryThenSecondary = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryThenSecondary" />
      <MemberSignature Language="VB.NET" Value="PrimaryThenSecondary" />
      <MemberSignature Language="F#" Value="PrimaryThenSecondary = 1" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryThenSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Anforderungen werden stets zuerst an den primären Speicherort gesendet. Wenn eine Anforderung fehlschlägt, wird sie an den sekundären Standort gesendet.
            </summary>
        <remarks>
            Wenn dieser Wert für Anforderungen, die nur für einen Standort gültig sind verwendet wird, wird der Client nur den zulässigen Speicherort abzielen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryOnly">
      <MemberSignature Language="C#" Value="SecondaryOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode SecondaryOnly = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryOnly" />
      <MemberSignature Language="VB.NET" Value="SecondaryOnly" />
      <MemberSignature Language="F#" Value="SecondaryOnly = 2" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Anforderungen werden stets an den sekundären Speicherort gesendet.
            </summary>
        <remarks>
            Wenn dieser Wert wird für Anforderungen verwendet, die nur für einen primären Standort funktionieren (erstellen, ändern und Löschen von APIs), die Anforderung schlägt fehl, auf dem Client.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryThenPrimary">
      <MemberSignature Language="C#" Value="SecondaryThenPrimary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode SecondaryThenPrimary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryThenPrimary" />
      <MemberSignature Language="VB.NET" Value="SecondaryThenPrimary" />
      <MemberSignature Language="F#" Value="SecondaryThenPrimary = 3" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryThenPrimary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            Anforderungen werden stets zuerst an den sekundären Speicherort gesendet. Wenn eine Anforderung fehlschlägt, wird er an den primären Speicherort gesendet.
            </summary>
        <remarks>
            Wenn dieser Wert für Anforderungen, die nur für einen Standort gültig sind verwendet wird, wird der Client nur den zulässigen Speicherort abzielen.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>